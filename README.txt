MC IMPORTACIONES — CATÁLOGO WEB (VERSIÓN INICIAL)

ARCHIVOS
- index.html: catálogo adaptable a celular y computadora.
- README.txt: estas instrucciones.

FUNCIONES
- Agregar, editar y borrar productos.
- Nombre, precio, categoría, stock/disponibilidad, descripción y URL de imagen.
- Búsqueda, filtro por categoría y orden por precio/nombre.
- Consulta individual por WhatsApp.
- Compartir enlace del catálogo.
- Crear/descargar QR del enlace público.
- Exportar/importar los productos como JSON.

INSTALACIÓN EN GITHUB PAGES
1. Descomprime el ZIP.
2. Entra a tu repositorio de GitHub Pages.
3. Sube index.html a la raíz del repositorio (reemplaza el anterior si corresponde).
4. En index.html busca ADMIN_PASSWORD y cambia "CAMBIA-ESTA-CLAVE" por una clave temporal propia.
5. Revisa WHATSAPP_NUMBER: está configurado como 51901148187. Cámbialo si quieres otro número.
6. Haz commit/push y espera a que GitHub Pages publique el sitio.
7. Abre la URL pública, ingresa a Administrar y agrega tus productos. Genera el QR desde el panel y descárgalo.

IMPORTANTE SOBRE ESTA VERSIÓN
Esta versión guarda los productos en el almacenamiento local del navegador (localStorage). Por eso, los productos que agregues desde tu computadora NO aparecerán automáticamente en los celulares de tus clientes ni en otros dispositivos. El QR sí abre la página pública, pero el catálogo compartido requiere una base de datos en línea.
Además, la contraseña de administración incluida en un archivo HTML público NO es seguridad real: una persona técnica puede verla en el código. No uses esta versión para información privada ni como sistema de inventario crítico.

PARA LA SIGUIENTE VERSIÓN PÚBLICA
Para que tú agregues productos desde tu computadora y todos los clientes vean los mismos datos, hay que conectar una base de datos en línea (por ejemplo, Supabase) con autenticación real y reglas de seguridad. La clave privada de administración nunca debe guardarse en el HTML público. También se puede añadir carga de imágenes desde un panel de administración.
