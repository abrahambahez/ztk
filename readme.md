# Prototipo de zettelkasten v5

Este repositorio es una prueba de un nuevo zettelkasten. Con él, estoy tratando de abandonar Obsidian y, con ello, migrando a una nueva lógica de trabajo con notas.

Estas son algunas de las reglas que creo que puede tener:

- **Centrado en la prosa**. No *frontmatter* ni cosas que tiendan a estructurar más allá del lenguaje natural
- **Escritura desde la terminal**: Neovim, zk, flujo de trabajo de escritorio
    - La obsesión por aumentar el zettelkasten desde el móvil/celular es ociosa e inútil. Este es trabajo intelectual estilo *Deepwork*
- **ID cronológicos**. Antes creía que, para poder buscar adecuadamente las notas, sus títulos deberían ser semánticos. Eso es cierto si solo dependes del administrador de archivos. Pero si buscas desde la terminal, puedes indexar los títulos h1 para buscar en ellos
- **Centrado en Git**: Como estoy pensando en el escritorio y la terminal, cada sesión de trabajo debe ser llevada por Git, como debe ser.
- **Publicable como un microblog**. Me siento ahor amás atraido por algo como [*The stream*](https://stream.thesephist.com/) de *The Sephist* que por algo como las [*Notas*](https://notes.andymatuschak.org/About_these_notes) de Andy Matuschak.
- No plugins, sino scripts o CLI

## Anatomía de una nota

1. Nombre de archivo estilo *timestamp* AAAAMMDDHHMM, añade el metadato de fecha de creación, permite orden cronológico y un ID único a cada nota
2. Un único título H1 al principio de cada nota, estilo `#`, esta es la base de la búsqueda.
3. Contenido prosa y markdown. Siguiendo la lógica de una nota atómica y el estilo de un micro-ensayo.
4. Densamente vinculado

## Notas de referencia

- Tienen como nombre de archivo su *@citekey* y una plantilla específica centrada en la prosa, no en los metadatos (para eso uso Zotero)
- Su contenido puede ser más largo

## Ejemplos

Ver [comunidades de disfrute](202506042053.md) como ejemplo.
