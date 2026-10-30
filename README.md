# Gota Silvestre: actualización para GitHub Pages

Esta descarga contiene la página actual con ocho jabones, las fotografías aprobadas, el logotipo de gota dorada, @gota_silvestre.cap y los pedidos al WhatsApp +573023261864. Incluye los avisos «Naturalmente únicos» y «Cuida tu piel» sobre el catálogo, y el buzón de sugerencias que abre WhatsApp con un mensaje ya escrito. Todos los precios siguen siendo provisionales: $15.000 COP.

IMPORTANTE: si modificaste precios u otros datos directamente en GitHub, esta descarga no contiene esos cambios. Haz primero una copia de tu repositorio y vuelve a aplicar esos ajustes antes de reemplazar tu página.

## 1. Descargar y descomprimir
1. Descarga el ZIP desde el mensaje de Lovable.
2. Busca el archivo en la carpeta Descargas de tu computador.
3. En Windows, haz clic derecho sobre el ZIP y elige «Extraer todo» y después «Extraer». En Mac, haz doble clic.
4. Abre la carpeta descomprimida y luego la carpeta «gota-silvestre».
5. Debes ver index.html, styles.css, README.md y la carpeta images. También se incluye .nojekyll, que puede estar oculto.

## 2. Hacer una copia de lo que ya tienes en GitHub
1. Entra en github.com e inicia sesión.
2. Abre el repositorio donde publicaste tu página.
3. Haz clic en el botón verde «Code» y después «Download ZIP».
4. Guarda esa copia por si necesitas recuperar tus cambios anteriores.

## 3. Subir la nueva versión al mismo repositorio
1. En tu repositorio, abre la pestaña «Code».
2. Comprueba que estás en la rama «main», o la misma rama que usa tu publicación.
3. Haz clic en «Add file» y después «Upload files».
4. Arrastra index.html, styles.css, README.md y la carpeta images desde DENTRO de la carpeta gota-silvestre. Si puedes ver .nojekyll, inclúyelo también; esta página funciona sin él si no aparece.
5. NO subas el archivo ZIP ni la carpeta exterior gota-silvestre: index.html debe quedar directamente en la raíz del repositorio.
6. GitHub reemplazará los archivos con el mismo nombre y añadirá los nuevos. Las carpetas antiguas assets pueden permanecer: la página nueva no las utiliza.
7. En «Commit changes», escribe «Actualizar página con avisos y buzón de sugerencias».
8. Si aparece la opción, elige guardar directamente en la rama de publicación. Pulsa «Commit changes» para confirmar.
9. Si necesitas conservar precios distintos que habías puesto en GitHub, ajusta primero la nueva copia o edita index.html después de subirla, como se explica abajo.

## 4. Confirmar GitHub Pages
1. En el repositorio, haz clic en «Settings» y después en «Pages» en el menú izquierdo.
2. En «Build and deployment», elige «Deploy from a branch» si aún no está seleccionado.
3. En «Branch», selecciona «main» (o tu rama de publicación) y «/(root)». Haz clic en «Save» si cambiaste algo.
4. Si Pages ya estaba configurado así, no necesitas configurarlo otra vez.
5. Abre «Actions» para comprobar que la publicación termina con una marca verde. Puede tardar unos minutos.
6. Regresa a «Settings → Pages» y pulsa «Visit site» cuando esté disponible.
7. Recarga tu página. Si todavía ves la versión anterior, prueba Ctrl+F5 en Windows o Cmd+Shift+R en Mac.
8. Comprueba que aparecen ocho jabones, los dos avisos sobre el catálogo y el buzón de sugerencias al final. Verifica que los botones «Pedir por WhatsApp» y «Dejar una sugerencia por WhatsApp» abren tu número con el mensaje correspondiente.

## 5. Cambiar precios desde GitHub
1. En «Code», haz clic en index.html y después en el icono del lápiz («Edit this file»).
2. Busca el nombre del jabón que quieres cambiar, usando Ctrl+F en Windows o Cmd+F en Mac.
3. Dentro de ese mismo bloque del producto, localiza $15.000 y reemplaza SOLO el precio; conserva los signos < y > y el resto del texto.
4. Repite para cada jabón que quieras actualizar. Hay ocho precios independientes.
5. Pulsa «Commit changes», escribe un mensaje como «Actualizar precios» y confirma.
6. Espera a que «Actions» termine y vuelve a revisar la página publicada.

## Notas
- Esta es una copia estática preparada para GitHub Pages, no el proyecto editable de Lovable. No necesitas instalar programas, Node ni ejecutar comandos para publicarla.
- Todas las fotos y el icono están incluidos en images y usan rutas relativas; funcionan dentro del nombre de tu repositorio.
- Las fuentes se cargan desde Google Fonts; sin conexión se usan fuentes de respaldo.
- No se ha entrado en tu cuenta ni publicado o modificado tu repositorio.
- Lovable y esta copia de GitHub Pages no se actualizan automáticamente entre sí.
