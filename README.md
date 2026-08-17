# Material Extra · Repositorio de subida

Este repositorio es un buzón público. **Cualquier persona con cuenta
de GitHub puede subir un archivo, sin que nadie tenga que darle
permiso de antemano.** Se hace por fork + Pull Request, y todo el
proceso se valida y fusiona solo — nadie tiene que revisarlo a mano.

## Cómo subir un archivo

1. Haz **fork** de este repositorio (botón "Fork" arriba a la
   derecha de la página de GitHub).
2. En tu fork, agrega tu archivo dentro de la carpeta `uploads/`.
3. **Nómbralo así:** `<ramo>_<titulo>.<extension>`, todo en
   minúsculas, palabras separadas por guion (`-`), y el ramo separado
   del título por guion bajo (`_`).

   Ejemplos válidos:
   ```
   algebra-lineal_espacios-vectoriales.pdf
   calculo_limites-y-continuidad.pdf
   fisica-general_cinematica.docx
   ```

   Ejemplos **inválidos**:
   ```
   Algebra Lineal - Espacios Vectoriales.pdf   (mayúsculas y espacios)
   espaciosvectoriales.pdf                      (falta el "_")
   ```

4. Haz commit en tu fork y abre un **Pull Request** hacia `main` de
   este repositorio.
5. Una Action valida automáticamente el nombre, el tamaño, y que tu
   PR solo haya tocado `uploads/`. Si todo está bien, el PR se
   fusiona solo en un par de minutos. El archivo pasa al sitio
   principal y desaparece de este buzón. No hace falta avisarle a
   nadie ni esperar aprobación.
6. Si algo está mal, la Action te lo deja como comentario en el
   mismo PR explicando qué corregir. Corrige el archivo o el nombre
   y vuelve a hacer push a la misma rama de tu fork — el PR se
   revalida solo, no hace falta abrir uno nuevo.

## Sobre la primera vez que subes algo

Por seguridad, GitHub pide que alguien con acceso de escritura a
este repo apruebe manualmente la primera vez que corre una Action
para una cuenta de GitHub **recién creada y sin actividad previa**.
Si tu cuenta ya tiene algo de historial (así sea de otro proyecto),
esto normalmente no debería pasarte. Es la única excepción al
"sin permisos" — la impone GitHub como protección antiabuso, no
nosotros, y solo puede aplicar una vez por cuenta nueva.

## Reglas

- Solo se aceptan archivos hasta 25 MB.
- Extensiones permitidas: `pdf, docx, pptx, xlsx, ipynb, png, jpg,
  jpeg, txt, md` (se puede ampliar editando el workflow).
- El Pull Request **solo puede agregar** archivos nuevos dentro de
  `uploads/`. No se permite editar ni borrar material ya publicado,
  ni tocar ningún otro archivo del repositorio (por ejemplo los
  workflows de `.github/`) — cualquier intento de eso rechaza el PR
  completo automáticamente.