## Español
Guía por [@nami-stuff](https://www.tumblr.com/nami-stuff), editada por [@knownyurimaxxer](https://www.tumblr.com/knownyurimaxxer). Puedes ver una *live demo* de la galería [AQUÍ](https://knownyurimaxxer.github.io/utility-gallery/).

### ¿Cómo instalo la galería?
1. Crea una cuenta de **Github**.
2. Crea una *fork* de [ESTE](https://github.com/knownyurimaxxer/utility-gallery) repositorio. Se hace con el botón de *fork* (asegúrate que `Copy the main branch only` esté marcado).
3. Si quieres editar el *HTML* o *CSS* para darles tu estilo personal, es el momento. Los archivos a editar son `.github/workflows/resources/root-index.html`, `.github/workflows/resources/branch-index.html` y `.github/workflows/resources/style.css`.

   *¡Si vas a realizar una fork base para tu idioma, recuerda añadirte en los créditos! (y editar el enlace en este `README.md` para que apunte a tu repositorio).*
4. Ve a la configuración del repositorio en **Settings** (recomiendo deshabilitar todas las **Features** y **Comments**).
5. Selecciona **Pages** y en **Source** selecciona **Github Actions**.
6. Ahora selecciona **Environments** y, una vez dentro, haz *click* en **github-pages**. En **Deployment branches and tags** selecciona **No restriction**.

### ¿Cómo funciona la galería?
La galería funciona usando ramas para cada conjunto de imágenes, lo que genera una estructura donde cada grupo es listado con sus respectivos subgrupos debajo y cada subgrupo tiene una carpeta con sus gráficos.

### ¿Cómo añadir tus gráficos?
1. Crea una nueva rama de `main` desde **New branch** (tienes que hacer *click* donde dice `main` y luego **View all branches**) y dale un nombre con la siguiente estructura: `nombre-del-grupo\nombre-del-subgrupo` (ejemplo: `tuberculo\patata`).

   *No uses espacios ni carácteres especiales.*
3. Renombra tus gráficos con el tipo de gráfico que representan (ejemplo: *avatar.png*). Si tienes múltiples variantes del mismo tipo de gráfico, dales un número (ejemplo: *firma1.png* y *firma2.png*).

   *Se permiten espacios, pero para urls más cortas, se recomienda no usarlos.*
4. Selecciona tu rama en el repositorio y sube tus gráficos desde **Add file**.
5. Espera a que se ejecute el deploy por si solo. Si no lo hace, ve a **Actions**, selecciona **Deploy to GitHub Pages** y dale a **Run workflow**.
7. Al terminar el proceso, la página se habrá actualizado (limpia cache, `ctrl+shift+r`, si no ves cambios). Accede al subgrupo y ahí estarán los gráficos que hayas subido, con su link listo para copiar.

> **NOTA:** Una vez creada la rama de un subgrupo, puedes seguir usándola para añadir o modificar gráficos. Si cambias un archivo por otro con el mismo nombre, se reemplazará ahí dónde lo estés usando. <ins>Vigila no borrar tu rama (o ninguna otra), o perderás todo</ins>.

## English
Guide by [@nami-stuff](https://www.tumblr.com/nami-stuff), edited by [@knownyurimaxxer](https://www.tumblr.com/knownyurimaxxer). You can view a *live demo* of the gallery [HERE](https://knownyurimaxxer.github.io/utility-gallery/).

### How do I install the gallery?
1. Create a **Github** account.
2. Create a *fork* of [THIS](https://github.com/knownyurimaxxer/utility-gallery) repository. This is done with the *fork* button (make sure `Copy the main branch only` is checked).
3. If you want to edit the *HTML* or *CSS* to give them your personal style, now is the time. The files to edit are `.github/workflows/resources/root-index.html`, `.github/workflows/resources/branch-index.html` and `.github/workflows/resources/style.css`.

   *If you're going to make a base fork for your language, remember to add yourself to the credits! (and edit the link in this `README.md` so it points to your repository).*
4. Go to the repository settings in **Settings** (I recommend disabling all **Features** and **Comments**).
5. Select **Pages** and in **Source** select **Github Actions**.
6. Now select **Environments** and, once inside, *click* on **github-pages**. In **Deployment branches and tags** select **No restriction**.

### How does the gallery work?
The gallery works using branches for each set of images, which generates a structure where each group is listed with its respective subgroups below and each subgroup has a folder with its graphics.

### How do I add my graphics?
1. Create a new branch from `main` from **New branch** (you have to *click* where it says `main` and then **View all branches**) and give it a name with the following structure: `group-name\subgroup-name` (example: `tuber\potato`).

   *Don't use spaces or special characters.*
3. Rename your graphics with the type of graphic they represent (example: *avatar.png*). If you have multiple variants of the same type of graphic, give them a number (example: *signature1.png* and *signature2.png*).

   *Spaces are allowed, but for shorter urls, it's recommended not to use them.*
4. Select your branch in the repository and upload your graphics from **Add file**.
5. Wait for the deploy to run on its own. If it doesn't, go to **Actions**, select **Deploy to GitHub Pages** and click **Run workflow**.
7. When the process finishes, the page will have updated (clear cache, `ctrl+shift+r`, if you don't see changes). Access the subgroup and there will be the graphics you've uploaded, with their link ready to copy.

> **NOTE:** Once a subgroup's branch is created, you can keep using it to add or modify graphics. If you change a file for another with the same name, it will be replaced wherever you're using it. <ins>Be careful not to delete your branch (or any other), or you'll lose everything</ins>.