# Extensi-n-gh-deb7
# Sintaxis básica de redacción y formato

Cree un formato sofisticado para el prose y el código en GitHub con una sintaxis sencilla.

## Headings

Para crear un encabezado, agregue uno a seis <kbd>#</kbd> símbolos antes del texto del encabezado. El número de <kbd>#</kbd> uso determinará el nivel de jerarquía y el tamaño del tipo de letra del encabezado.

```markdown
# A first-level heading
## A second-level heading
### A third-level heading
```

![Captura de pantalla de los encabezados GitHub Markdown representados que muestran los encabezados h1, h2 y h3 de ejemplo, que descienden en tamaño de tipo y peso visual para mostrar el nivel de jerarquía.](/assets/images/help/writing/headings-rendered.png)

Al usar dos o más encabezados, GitHub genera automáticamente una tabla de contenido a la que puede acceder haciendo clic en el icono de menú "Esquema" <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-list-unordered" aria-label="Table of Contents" role="img"><path d="M5.75 2.5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5Zm0 5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5Zm0 5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5ZM2 14a1 1 0 1 1 0-2 1 1 0 0 1 0 2Zm1-6a1 1 0 1 1-2 0 1 1 0 0 1 2 0ZM2 4a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path></svg> dentro del encabezado de archivo. Cada título de título aparece en la tabla de contenido y puede hacer clic en un título para ir a la sección seleccionada.

![Captura de pantalla de un archivo LÉAME con el menú desplegable de la tabla de contenidos mostrada. El icono de tabla de contenido se describe en naranja oscuro.](/assets/images/help/repository/headings-toc.png)

## Aplicar estilo al texto

Puede indicar énfasis con negrita, cursiva, tachado, subíndice o texto de superíndice en los campos y `.md` archivos de comentario.

| Style                                                                                | Syntax                                            | Atajo de teclado                         | Example                                 | Salida                                      |
| ------------------------------------------------------------------------------------ | ------------------------------------------------- | ---------------------------------------- | --------------------------------------- | ------------------------------------------- |
| Bold                                                                                 |                                                   |                                          |                                         |                                             |
| `** **` o `__ __`                                                                    |                                                   |                                          |                                         |                                             |
| <kbd>Command</kbd>+<kbd>B</kbd> (Mac) o <kbd>Ctrl</kbd>+<kbd>B</kbd> (Windows/Linux) | `**This is bold text**`                           |                                          |                                         |                                             |
| **Este es texto en negrita**                                                         |                                                   |                                          |                                         |                                             |
| Itálico                                                                              |                                                   |                                          |                                         |                                             |
| `* *` o `_ _`                                                                        |                                                   |                                          |                                         |                                             |
| <kbd>Command</kbd>+<kbd>I</kbd> (Mac) o <kbd>Ctrl</kbd>+<kbd>I</kbd> (Windows/Linux) | `_This text is italicized_`                       |                                          |                                         |                                             |
| *Este texto está en cursiva*                                                         |                                                   |                                          |                                         |                                             |
| Tachado                                                                              |                                                   |                                          |                                         |                                             |
| `~~ ~~` o `~ ~`                                                                      | Ninguno                                           | `~~This was mistaken text~~`             |                                         |                                             |
| ~~Se equivocó el texto~~                                                             |                                                   |                                          |                                         |                                             |
| Negrita y cursiva anidada                                                            |                                                   |                                          |                                         |                                             |
| `** **` y `_ _`                                                                      | Ninguno                                           | `**This text is _extremely_ important**` |                                         |                                             |
| **Este texto es *extremadamente* importante**                                        |                                                   |                                          |                                         |                                             |
| Todo en negrita y cursiva                                                            | `*** ***`                                         | Ninguno                                  | `***All this text is important***`      |                                             |
| ***Todo este texto es importante***                                                  | <!-- markdownlint-disable-line emphasis-style --> |                                          |                                         |                                             |
| Subíndice                                                                            | `<sub> </sub>`                                    | Ninguno                                  | `This is a <sub>subscript</sub> text`   | Este es un texto <sub>de subíndice</sub>    |
| Superíndice                                                                          | `<sup> </sup>`                                    | Ninguno                                  | `This is a <sup>superscript</sup> text` | Se trata de un texto <sup>superíndice</sup> |
| Subrayado                                                                            | `<ins> </ins>`                                    | Ninguno                                  | `This is an <ins>underlined</ins> text` | Se trata de un texto <ins>subrayado</ins>   |

## Texto citado

Puede entrecomillar texto con .<kbd>></kbd>

```markdown
Text that is not a quote

> Text that is a quote
```

El texto citado se indenta con una línea vertical a la izquierda y se muestra en color gris.

![Captura de pantalla de GitHub Markdown representada que muestra la diferencia entre texto normal y entre comillas.](/assets/images/help/writing/quoted-text-rendered.png)

> \[!NOTE]
> Al ver una conversación, puede citar automáticamente texto en un comentario resaltando el texto y escribiendo <kbd>R</kbd>. Para citar un comentario completo, haga clic en <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-kebab-horizontal" aria-label="El icono de kebab horizontal" role="img"><path d="M8 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3ZM1.5 9a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Zm13 0a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3Z"></path></svg>y, a continuación, **respuesta de comillas**. Para obtener más información sobre los métodos abreviados de teclado, vea [Atajos de teclado](/es/get-started/accessibility/keyboard-shortcuts).

## Citar código

Puede destacar código o comandos dentro de una oración con comillas invertidas simples. No se dará formato al texto dentro de las comillas invertidas. También puede presionar el <kbd>Command</kbd>+<kbd>E</kbd> (Mac) o <kbd>Ctrl</kbd>+<kbd>E</kbd> (Windows/Linux) para insertar los retrocesos de un bloque de código dentro de una línea de Markdown.

```markdown
Use `git status` to list all new or modified files that haven't yet been committed.
```

![Captura de pantalla de GitHub Markdown representada en la que se muestra que los caracteres rodeados por acentos se muestran en un tipo de ancho fijo, resaltado en gris claro.](/assets/images/help/writing/inline-code-rendered.png)

Para dar formato al código o al texto en su propio bloque diferenciado, use tres comillas invertidas.

````markdown
Some basic Git commands are:
```
git status
git add
git commit
```
````

![Captura de pantalla de GitHub Markdown representada que muestra un bloque de código simple sin resaltado de sintaxis.](/assets/images/help/writing/code-block-rendered.png)

Para más información, consulta [Crear y resaltar bloques de código](/es/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks).

Si editas fragmentos de código y tablas con frecuencia, puedes beneficiarte de habilitar una fuente de ancho fijo en todos los campos de comentarios de GitHub. Para más información, consulta [Acerca de la escritura y el formato en GitHub](/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github#enabling-fixed-width-fonts-in-the-editor).

## Modelos de color admitidos

En los temas, solicitudes de incorporación de cambios y discusiones, pueden destacar colores dentro de una oración utilizando comillas invertidas. Un modelo de color admitido entre comillas invertidas mostrará una visualización del color.

```markdown
The background color is `#ffffff` for light mode and `#000000` for dark mode.
```

![Captura de pantalla de la GitHub Markdown representada en la que se muestran cómo los valores HEX dentro de las marcas inversas crean pequeños círculos de color, aquí blanco y negro.](/assets/images/help/writing/supported-color-models-rendered.png)

Estos son los modelos de color admitidos actualmente.

| Color              | Syntax                      | Example                             | Salida                                                                                                                                                                                                  |
| ------------------ | --------------------------- | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HEX or Hexadecimal | <code>\`#RRGGBB\`</code>    | <code>\`#0969DA\`</code>            | ![Captura de pantalla de GitHub Markdown representada que muestra cómo aparece el valor HEX #0969DA con un círculo azul.](/assets/images/help/writing/supported-color-models-hex-rendered.png)          |
| RGB                | <code>\`rgb(R,G,B)\`</code> | <code>\`rgb(9, 105, 218)\`</code>   | ![Captura de pantalla de GitHub Markdown representada que muestra cómo aparece el valor RGB 9, 105, 218 con un círculo azul.](/assets/images/help/writing/supported-color-models-rgb-rendered.png)      |
| HSL                | <code>\`hsl(H,S,L)\`</code> | <code>\`hsl(212, 92%, 45%)\`</code> | ![Captura de pantalla de GitHub Markdown representada que muestra cómo aparece el valor de HSL 212, 92%, 45% con un círculo azul.](/assets/images/help/writing/supported-color-models-hsl-rendered.png) |

> \[!NOTE]
>
> * Un modelo de color admitido no puede tener espacios iniciales o finales dentro de las comillas invertidas.
> * La visualización del color solo se admite en incidencias, pull requests y discusiones.

## Enlaces

Puede crear un vínculo insertado ajustando el texto del vínculo entre corchetes `[ ]`y ajustando la dirección URL entre paréntesis `( )`. También puede usar el método abreviado de teclado <kbd>Comando</kbd>+<kbd>K</kbd> para crear un vínculo. Cuando haya seleccionado texto, puede pegar una dirección URL del Portapapeles para crear automáticamente un vínculo a partir de la selección.

También puede crear un hipervínculo de Markdown resaltando el texto y usando el método abreviado de teclado <kbd>Command</kbd>+<kbd>V</kbd>. Si desea reemplazar el texto por el vínculo, use el método abreviado de teclado <kbd>Command</kbd>+<kbd>Shift</kbd>+<kbd>V</kbd>.

`This site was built using [GitHub Pages](https://pages.github.com/).`

![Captura de pantalla de GitHub Markdown representada que muestra cómo el texto entre corchetes, "GitHub Pages", aparece como un hipervínculo azul.](/assets/images/help/writing/link-rendered.png)

> \[!NOTE]
> GitHub crea automáticamente vínculos cuando las direcciones URL válidas se escriben en un comentario. Para más información, consulta [Referencias y direcciones URL autovinculadas](/es/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls).

## Vínculos de sección

Puede vincular directamente a cualquier sección que tenga un encabezado. Para ver el delimitador generado automáticamente en un archivo representado, mantenga el puntero sobre el encabezado de sección para exponer el icono de <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-link" aria-label="the link" role="img"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg> y haga clic en el icono para mostrar el delimitador en el explorador.

![Captura de pantalla de un archivo README de un repositorio. A la izquierda de un encabezado de sección, se destaca un icono de vínculo en naranja oscuro.](/assets/images/help/repository/readme-links.png)

Si necesita determinar el delimitador de un encabezado en un archivo que está editando, puede usar las siguientes reglas básicas:

* Las letras se convierten en minúsculas.
* Los espacios se reemplazan por guiones (`-`). Se quitan cualquier otro espacio en blanco o caracteres de puntuación.
* Se quitan los espacios en blanco iniciales y finales.
* Se quita el formato de marcado, dejando solo el contenido (por ejemplo, `_italics_` se convierte en `italics`).
* Si el delimitador generado automáticamente para un encabezado es idéntico a un delimitador anterior en el mismo documento, se genera un identificador único anexando un guión y un entero de incremento automático.

Para obtener información más detallada sobre los requisitos de fragmentos de URI, consulte [RFC 3986: Identificador uniforme de recursos (URI): Sintaxis genérica, sección 3.5](https://www.rfc-editor.org/rfc/rfc3986#section-3.5).

El bloque de código siguiente muestra las reglas básicas que se usan para generar anclajes a partir de encabezados en contenido representado.

```markdown
# Example headings

## Sample Section

## This'll be a _Helpful_ Section About the Greek Letter Θ!
A heading containing characters not allowed in fragments, UTF-8 characters, two consecutive spaces between the first and second words, and formatting.

## This heading is not unique in the file

TEXT 1

## This heading is not unique in the file

TEXT 2

# Links to the example headings above

Link to the sample section: [Link Text](#sample-section).

Link to the helpful section: [Link Text](#thisll-be-a-helpful-section-about-the-greek-letter-Θ).

Link to the first non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file).

Link to the second non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file-1).
```

> \[!NOTE]
> Si edita un encabezado o cambia el orden de los encabezados con anclajes "idénticos", también deberá actualizar los vínculos a esos encabezados, ya que los delimitadores cambiarán.

## Vínculos relativos

Puedes definir enlaces relativos y rutas de imagen en los archivos representados para ayudar a que los lectores naveguen hasta otros archivos de tu repositorio.

Un enlace relativo es un enlace que es relativo al archivo actual. Por ejemplo, si tiene un archivo Léame en la raíz del repositorio y tiene otro archivo en *docs/CONTRIBUTING.md*, el vínculo relativo a *CONTRIBUTING.md* en el archivo Léame podría tener este aspecto:

```text
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

GitHub transformará de manera automática el enlace relativo o la ruta de imagen en cualquier rama en la que te encuentres actualmente, de modo que el enlace o ruta siempre funcione. La ruta de acceso del vínculo será relativa al archivo actual. Los vínculos que comienzan por `/` serán relativos a la raíz del repositorio. Puede usar todos los operandos de vínculo relativos, como `./` y `../`.

El texto del vínculo debe estar en una sola línea. El ejemplo siguiente no funcionará.

```markdown
[Contribution
guidelines for this project](docs/CONTRIBUTING.md)
```

Los enlaces relativos son más sencillos para los usuarios que clonan tu repositorio. Puede que los enlaces absolutos no funcionen en los clones de tu repositorio. Recomendamos usar enlaces relativos para consultar los archivos dentro de tu repositorio.

## Anclajes personalizados

Puede usar etiquetas de anclaje HTML estándar (`<a name="unique-anchor-name"></a>`) para crear puntos de anclaje de navegación para cualquier ubicación del documento. Para evitar referencias ambiguas, use un esquema de nomenclatura único para etiquetas de anclaje, como agregar un prefijo al valor del `name` atributo.

> \[!NOTE]
> Los delimitadores personalizados no se incluirán en el esquema o tabla de contenido del documento.

Puede vincular a un delimitador personalizado mediante el valor del `name` atributo que proporcionó el delimitador. La sintaxis es exactamente la misma que cuando enlaza a un ancla que se genera automáticamente para un encabezado.

Por ejemplo:

```markdown
# Section Heading

Some body text of this section.

<a name="my-custom-anchor-point"></a>
Some text I want to provide a direct link to, but which doesn't have its own heading.

(… more content…)

[A link to that custom anchor](#my-custom-anchor-point)
```

> \[!TIP]
> Las anclas personalizadas no son consideradas por el comportamiento de nomenclatura y numeración automática de los vínculos de encabezado.

## Saltos de línea

Si está escribiendo problemas, solicitudes de incorporación de cambios o discusiones en un repositorio, GitHub representará automáticamente un salto de línea:

```markdown
This example
Will span two lines
```

Sin embargo, si está escribiendo en un archivo .md, el ejemplo anterior se mostraría en una única línea sin un fin de línea. Para crear un salto de línea en un archivo .md, deberá incluir uno de los siguientes elementos:

* Incluya dos espacios al final de la primera línea.
  <pre>
  This example&nbsp;&nbsp;
  Will span two lines
  </pre>

* Incluya una barra diagonal inversa al final de la primera línea.

  ```markdown
  This example\
  Will span two lines
  ```

* Incluya una etiqueta de salto de una sola línea HTML al final de la primera línea.

  ```markdown
  This example<br/>
  Will span two lines
  ```

Si deja una línea en blanco entre dos líneas, tanto en los archivos .md como en la sintaxis Markdown en incidencias, solicitudes de extracción y discusiones, las líneas se mostrarán separadas por la línea en blanco.

```markdown
This example

Will have a blank line separating both lines
```

## Imágenes

Puede mostrar una imagen agregando <kbd>!</kbd> y ajuste del texto alternativo en `[ ]`. El texto alternativo es un texto corto equivalente a la información de la imagen. A continuación, ajuste el vínculo de la imagen entre paréntesis `()`.

`![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)`

![Captura de pantalla de un comentario sobre un problema de GitHub que muestra una imagen, agregada en Markdown, de un Octocat sonriendo y levantando un tentáculo.](/assets/images/help/writing/image-rendered.png)

GitHub admite la inserción de imágenes en sus problemas, solicitudes de incorporación de cambios, debates, comentarios y `.md` archivos. Puede mostrar una imagen desde el repositorio, agregar un vínculo a una imagen en línea o cargar una imagen. Para obtener más información, consulte [Carga de recursos](#uploading-assets).

> \[!NOTE]
> Cuando desee mostrar una imagen que se encuentra en el repositorio, use vínculos relativos en lugar de vínculos absolutos.

Estos son algunos ejemplos para usar vínculos relativos para mostrar una imagen.

| Context                                                                                 | Vínculo relativo                                                       |
| --------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| En un `.md` archivo de la misma rama                                                    | `/assets/images/electrocat.png`                                        |
| En un `.md` archivo de otra rama                                                        | `/../main/assets/images/electrocat.png`                                |
| En las incidencias, solicitudes de extracción y comentarios del repositorio             | `../blob/main/assets/images/electrocat.png?raw=true`                   |
| En un `.md` archivo de otro repositorio                                                 | `/../../../../github/docs/blob/main/assets/images/electrocat.png`      |
| En problemas, solicitudes de incorporación de cambios y comentarios de otro repositorio | `../../../github/docs/blob/main/assets/images/electrocat.png?raw=true` |

> \[!NOTE]
> Los dos últimos vínculos relativos de la tabla anterior funcionarán para las imágenes de un repositorio privado solo si el visor tiene al menos acceso de lectura al repositorio privado que contiene estas imágenes.

Para obtener más información, vea [Vínculos relativos](#relative-links).

### Elemento Imagen

Se admite el `<picture>` elemento HTML.

## Lists

Puede crear una lista sin ordenar si precede una o varias líneas de texto con <kbd>-</kbd>, <kbd>\*</kbd>o <kbd>+</kbd>.

```markdown
- George Washington
* John Adams
+ Thomas Jefferson
```

![Captura de pantalla de GitHub Markdown representada en la que se muestra una lista con viñetas de los nombres de los tres primeros presidentes estadounidenses.](/assets/images/help/writing/unordered-list-rendered.png)

Para ordenar la lista, precede a cada línea con un número.

```markdown
1. James Madison
2. James Monroe
3. John Quincy Adams
```

![Captura de pantalla de GitHub Markdown representada en la que se muestra una lista numerada de los nombres de los presidentes cuarto, quinto y sexto estadounidense.](/assets/images/help/writing/ordered-list-rendered.png)

### Listas anidadas

Puede crear una lista anidada al sangrar uno o varios elementos de lista para ubicarlos debajo de otro elemento.

Para crear una lista anidada mediante el editor web en GitHub o un editor de texto que use una fuente monoespacial, como [Visual Studio Code](https://code.visualstudio.com/), puede alinear la lista visualmente. Escriba caracteres de espacio delante del elemento de lista anidado hasta que el carácter de marcador de lista (<kbd>-</kbd> o <kbd>\*</kbd>) se encuentra directamente debajo del primer carácter del texto del elemento encima de él.

```markdown
1. First list item
   - First nested list item
     - Second nested list item
```

> \[!NOTE]
> En el editor basado en web, puede sangr o sangr una o varias líneas de texto resaltando primero las líneas deseadas y, a continuación, usando <kbd>tabulación</kbd> o <kbd>tabulación mayús</kbd>+ respectivamente.<kbd></kbd>

![Captura de pantalla de Markdown en Visual Studio Code que muestra la sangría de líneas numeradas anidadas y viñetas.](/assets/images/help/writing/nested-list-alignment.png)

![Captura de pantalla de GitHub Markdown representada que muestra un elemento numerado seguido de viñetas anidadas en dos niveles diferentes de anidamiento.](/assets/images/help/writing/nested-list-example-1.png)

Para crear una lista anidada en el editor de comentarios en GitHub, que no usa una fuente monoespacial, puede examinar el elemento de lista inmediatamente encima de la lista anidada y contar el número de caracteres que aparecen antes del contenido del elemento. A continuación, escriba ese número de caracteres de espacio delante del elemento de lista anidado.

En este ejemplo, podría agregar un elemento de lista anidado bajo el elemento `100. First list item` de lista mediante la sangría del elemento de lista anidado como mínimo de cinco espacios, ya que hay cinco caracteres (`100. `) antes `First list item`de .

```markdown
100. First list item
     - First nested list item
```

![Captura de pantalla de GitHub Markdown representada que muestra un elemento numerado precedido por el número 100 seguido de un elemento con viñetas anidado de un nivel.](/assets/images/help/writing/nested-list-example-3.png)

Puede crear varios niveles de listas anidadas mediante el mismo método. Por ejemplo, dado que el primer elemento de lista anidado tiene siete caracteres (`␣␣␣␣␣-␣`) antes del contenido `First nested list item`de la lista anidada, tendría que sangr el segundo elemento de lista anidado por al menos dos caracteres más (nueve espacios como mínimo).

```markdown
100. First list item
     - First nested list item
       - Second nested list item
```

![Captura de pantalla de GitHub Markdown representada que muestra un elemento numerado precedido por el número 100 seguido de viñetas en dos niveles diferentes de anidamiento.](/assets/images/help/writing/nested-list-example-2.png)

Para obtener más ejemplos, consulte el [GitHub Especificación de Markdown con sabor](https://github.github.com/gfm/#example-265).

## Listas de tareas

Para crear una lista de tareas, debe añadir como prefijo un guion y espacio, seguido de `[ ]` a los elementos de la lista. Para marcar una tarea como completada, use `[x]`.

```markdown
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```

![Captura de pantalla que muestra la versión representada de Markdown. Las referencias a problemas se representan como títulos del problema.](/assets/images/help/writing/task-list-rendered-simple.png)

Si una descripción del elemento de lista de tareas comienza por un paréntesis, deberá escaparla con <kbd>\\</kbd>:

`- [ ] \(Optional) Open a followup issue`

Para más información, consulta [Acerca de las listas de tareas](/es/get-started/writing-on-github/working-with-advanced-formatting/about-task-lists).

## Mencionar personas y equipos

Puede mencionar a una persona o [equipo](/es/organizations/organizing-members-into-teams) en GitHub escribiendo <kbd>@</kbd> más su nombre de usuario o nombre de equipo. Esto desencadenará una notificación y llamará su atención a la conversación. Las personas también recibirán una notificación si edita un comentario para mencionar su nombre de usuario o nombre de equipo. Para obtener más información sobre las notificaciones, consulta [Acerca de las notificaciones](/es/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/about-notifications).

> \[!NOTE]
> Una persona solo recibirá una notificación sobre una mención si la persona tiene acceso de lectura al repositorio y, si el repositorio es propiedad de una organización, la persona es miembro de la organización.

`@github/support What do you think about these updates?`

![Captura de pantalla de GitHub Markdown representada que muestra cómo el equipo menciona "@github/support" se representa como texto en negrita y en negrita.](/assets/images/help/writing/mention-rendered.png)

Cuando menciona un equipo principal, los miembros de sus equipos secundarios también reciben notificaciones, lo que simplifica la comunicación con varios grupos. Para más información, consulta [Acerca de los equipos de la organización](/es/organizations/organizing-members-into-teams/about-teams).

Al escribir un <kbd>@</kbd> símbolo se mostrará una lista de personas o equipos en un proyecto. La lista se filtra a medida que escribe, de modo que, una vez que encuentre el nombre de la persona o equipo que busca, puede usar las teclas de flecha para seleccionarlo y presionar Tabulador o Enter para completar el nombre. En el caso de los equipos, escriba y @organization/team-name todos los miembros de ese equipo se suscribirán a la conversación.

Los resultados de autocompletado están restringidos a los colaboradores del repositorio y a cualquier otro participante del hilo.

## Hacer referencia a problemas y solicitudes de incorporación de cambios

Puede mostrar una lista de problemas sugeridos y solicitudes de incorporación de cambios en el repositorio escribiendo <kbd>#</kbd>. Escriba el número o título del problema o solicitud de incorporación de cambios para filtrar la lista y, a continuación, presione la tecla de tabulación o Intro para completar el resultado seleccionado.

Para más información, consulta [Referencias y direcciones URL autovinculadas](/es/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls).

## Hacer referencia a recursos externos

Si se configuran las referencias autovinculadas personalizadas para un repositorio, entonces las referencias a recursos externos, como un informe de problemas de JIRA o un ticket de Zendesk, se convertirán en vínculos acortados. Para saber qué autovínculos se encuentran disponibles en tu repositorio, contacta a alguien con permisos administrativos sobre el mismo. Para más información, consulta [Configurar enlaces automáticos para referenciar recursos externos](/es/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/configuring-autolinks-to-reference-external-resources).

## Carga de recursos

Puede cargar recursos como imágenes arrastrando y colocando, seleccionando desde un explorador de archivos o pegando. Puede cargar recursos en problemas, solicitudes de incorporación de cambios, comentarios y `.md` archivos en el repositorio.

## Uso de emojis

Puede agregar emoji a la escritura escribiendo `:EMOJICODE:`, dos puntos seguidos del nombre del emoji.

`@octocat :+1: This PR looks great - it's ready to merge! :shipit:`

![Captura de pantalla de GitHub Markdown representada que muestra cómo los códigos emoji para +1 y shipit se representan visualmente como emoji.](/assets/images/help/writing/emoji-rendered.png)

Escritura <kbd>:</kbd> mostrará una lista de emojis sugeridos. La lista filtrará a medida que escriba, por lo que una vez que encuentre el emoji que busca, presione **Tab** o **Entrar** para completar el resultado resaltado.

Para obtener una lista completa de los códigos y emoji disponibles, consulta [emoji-Cheat-Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/github-actions-auto-update/README.md).

## Paragraphs

Puede crear un nuevo párrafo dejando una línea en blanco entre líneas de texto.

## Footnotes

Puede agregar notas al pie al contenido mediante esta sintaxis de corchetes:

```text
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, add 2 spaces to the end of a line.  
This is a second line.
```

La nota al pie se representará de la siguiente manera:

![Captura de pantalla de Markdown representada que muestra los números de superíndice usados para indicar notas al pie, junto con saltos de línea opcionales dentro de una nota.](/assets/images/help/writing/footnote-rendered.png)

> \[!NOTE]
> La posición de una nota al pie en Markdown no influye en dónde se mostrará la nota al pie. Puede escribir una nota al pie justo después de la referencia a dicha nota, y la nota al pie se seguirá mostrando en la parte inferior del documento Markdown. Las notas al pie no se admiten en wikis.

## Alerts

**Las alertas**, también conocidas como **llamadas** o **admoniciones**, son una extensión de Markdown basada en la sintaxis blockquote que puede usar para resaltar la información crítica. En GitHub, se muestran con colores e iconos distintivos para indicar la importancia del contenido.

Use alertas solo cuando sean cruciales para el éxito del usuario y limite a uno o dos por artículo para evitar sobrecargar el lector. Además, debe evitar colocar alertas consecutivamente. Las alertas no se pueden anidar dentro de otros elementos.

Para agregar una alerta, use una línea blockquote especial que especifique el tipo de alerta, seguido de la información de alerta en un blockquote estándar. Hay cinco tipos de alertas disponibles:

```markdown
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```

Estas son las alertas representadas:

![Captura de pantalla de alertas de Markdown renderizadas mostrando cómo se representan las notas, las sugerencias, lo importante, las advertencias y las precauciones con texto e iconos de diferentes colores.](/assets/images/help/writing/alerts-rendered.png)

## Ocultar contenido con comentarios

Puede indicar a GitHub que oculten el contenido de Markdown representado colocando el contenido en un comentario HTML.

```text
<!-- This content will not appear in the rendered Markdown -->
```

## Omitir el formato de Markdown

Puede indicar a GitHub que omitan (o escape) formato Markdown mediante <kbd>\\</kbd> antes del carácter Markdown.

`Let's rename \*our-new-project\* to \*our-old-project\*.`

![Captura de pantalla de la GitHub Markdown representada que muestra cómo las barras diagonales inversas impiden la conversión de asteriscos en cursiva.](/assets/images/help/writing/escaped-character-rendered.png)

Para obtener más información sobre las barras diagonales inversas, vea Daring [Fireball's Markdown Syntax( Sintaxis markdown](https://daringfireball.net/projects/markdown/syntax#backslash) de Daring Fireball).

> \[!NOTE]
> El formato Markdown no se omitirá en el título de un problema o una solicitud de incorporación de cambios.

## Desactivar la renderización de Markdown

Cuando ves un archivo de lenguaje de marcado, puedes hacer clic en **Código** en la parte superior de este para inhabilitar la representación de lenguaje de marcado y ver en su lugar el código fuente del archivo.

![Captura de pantalla de un archivo Markdown en un repositorio que muestra las opciones para interactuar con el archivo. Un botón, con la etiqueta "Código", está resaltado en naranja oscuro.](/assets/images/help/writing/display-markdown-as-source-global-nav-update.png)

El inhabilitar la interpretación de lenguaje de marcado te permite utilizar las características de vista de código fuente, tales como el enlazado de líneas, el cual no es posible cuando se está viendo un archivo interpretado en lenguaje de marcado.

## Lectura adicional

* [Especificación de GitHub Flavored Markdown](https://github.github.com/gfm/)
* [Acerca de la escritura y el formato en GitHub](/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github)
* [Trabajar con formato avanzado](/es/get-started/writing-on-github/working-with-advanced-formatting)
* [Inicio rápido para escribir en GitHub](/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)
