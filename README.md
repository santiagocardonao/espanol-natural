# español-natural

Una *skill* para Claude (Claude Code y Cowork) que hace que la IA **escriba en español como un hablante nativo**, no como una traducción del inglés.

El "español de IA" es correcto pero plano: estructuras calcadas del inglés, muletillas de relleno ("es importante señalar que...", "al final del día"), rayas por todos lados y un entusiasmo uniforme que ninguna persona usa. Esta skill lo detecta y lo arregla.

## Qué hace

- **Reescribe** texto para que suene natural (modo por defecto).
- **Revisa** y marca los problemas sin tocar el texto.
- **Edita** un archivo en el sitio.
- Ajusta el **dialecto**: neutro latinoamericano por defecto, o colombiano, mexicano, rioplatense o de España.

Cubre calcos del inglés, muletillas de IA, conectores repetidos, puntuación española (¿ ¡, mayúsculas de título, coma decimal) y tono de folleto.

## Instalación

### En Claude Code

Clona el repo y enlázalo a tu carpeta de skills:

```bash
git clone https://github.com/USUARIO/espanol-natural.git ~/Developer/espanol-natural
ln -s ~/Developer/espanol-natural ~/.claude/skills/espanol-natural
```

(Reemplaza `USUARIO` por tu usuario de GitHub.)

### En Cowork

Copia la carpeta a la ubicación de skills de tu espacio de Cowork, o instálala como parte de un plugin. La skill es un único `SKILL.md`, así que funciona en cualquier asistente compatible con el formato [agentskills.io](https://agentskills.io).

## Uso

Basta con pedirlo en lenguaje natural:

- "Escribe esto en español natural, que no suene a IA."
- "Revisa mi español, creo que suena a traducción."
- "Arréglame el español de `borrador.md`."
- "Reescribe en español colombiano."

## Ejemplo

**Antes (español de IA):**
> "En el mundo actual, aprovechar el poder de la IA es clave. Nuestra robusta plataforma ofrece una experiencia sin fisuras, empoderando a los usuarios. ¡Es un cambio de juego!"

**Después (natural):**
> "La IA ya no es opcional. Nuestra plataforma es fácil de usar y le da a cada persona el control de su trabajo. Los equipos que la probaron ahorraron unas seis horas a la semana."

## Licencia

MIT © Santiago Cardona Ortiz
