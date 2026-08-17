# Material Extra · Repositorio de subida

Este repositorio es un buzón público. **Cualquier persona con cuenta
de GitHub puede subir un archivo.** Se hace por fork más Pull Request, y todo el
proceso se valida y fusiona solo.

## Cómo subir un archivo

1. Haz **fork** de este repositorio.
2. En tu fork, agrega tu archivo dentro de la carpeta `uploads/`.
3. **Nómbralo así:** `<ramo>_<título>.<extensión>`, todo en
   minúsculas, palabras separadas por guion (`-`), y el ramo separado
   del título por guion bajo (`_`).

   Ejemplos válidos:
   ```
   algebra-lineal_espacios-vectoriales.pdf
   calculo_limites-y-continuidad.pdf
   programacion-avanzada_tuplas.ipynb
   ```

   Ejemplos **inválidos**:
   ```
   Algebra Lineal - Espacios Vectoriales.pdf   (mayúsculas y espacios)
   espaciosvectoriales.pdf                      (falta el "_")
   ```

4. Haz commit en tu fork y abre un **Pull Request** hacia `main` de
   este repositorio.
5. Se valida automáticamente el nombre, el tamaño, y que tu
   Pull Request solo haya tocado `uploads/`.
6. Si algo está mal, corrige el archivo o el nombre
   y vuelve a hacer push a la misma rama de tu fork.

## Reglas

- Solo se aceptan archivos hasta 25 MB.
- Extensiones permitidas: `pdf, docx, pptx, xlsx, ipynb, png, jpg,
  jpeg, txt, md` (se puede ampliar editando el workflow).
- El Pull Request **solo puede agregar** archivos nuevos dentro de
  `uploads/`.
