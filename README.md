# VideoWallPreview

Simulador interactivo de VideoWall para previsualización y organización de pantallas, desarrollado para Grupo Werthein.

## Descripción

Este proyecto es una aplicación web en HTML puro que permite simular la disposición de un VideoWall de 30 pantallas (dos filas de 15), facilitando la carga, organización y exportación de imágenes para cada pantalla. Ideal para previsualizar configuraciones antes de la implementación física.

## Características principales

- **Carga de imágenes**: Arrastra y suelta o selecciona imágenes para cada pantalla individualmente.
- **Identificación visual**: Cada pantalla tiene un identificador único (A01-A22, B08-B30) y muestra el nombre del archivo cargado.
- **Eliminación rápida**: Borra imágenes de pantallas individuales o limpia todo el VideoWall con un clic.
- **Exportación**: Descarga una imagen del VideoWall completo en alta resolución.
- **Pantalla completa**: Visualiza el VideoWall en modo pantalla completa para presentaciones o revisiones.
- **Interfaz moderna**: Diseño responsivo, oscuro y minimalista.

## Uso

1. **Abrir el archivo**: Descarga o clona el repositorio y abre `Simulador Werthein.html` en tu navegador.
2. **Cargar imágenes**: Haz clic en cualquier pantalla o arrastra imágenes sobre ella para asignarlas. Puedes cargar varias imágenes a la vez.
3. **Eliminar imágenes**: Usa la "×" en cada pantalla o el botón "Limpiar Todo" para reiniciar.
4. **Exportar**: Haz clic en "Exportar Imagen" para descargar una captura del VideoWall.
5. **Pantalla completa**: Usa el botón correspondiente para maximizar la visualización.

## Estructura del proyecto

- `Simulador Werthein.html`: Archivo principal, contiene todo el código HTML, CSS y JavaScript necesario.

## Tecnologías utilizadas

- HTML5, CSS3, JavaScript puro
- [html2canvas](https://html2canvas.hertzen.com/) para la exportación de imágenes

## Despliegue en Vercel

Este proyecto es estático y puede desplegarse fácilmente en Vercel:

1. **Importa el repositorio en Vercel** desde https://vercel.com/new
2. **Configura como proyecto estático** (no requiere build, ni frameworks)
3. **Establece `Simulador Werthein.html` como archivo de inicio**:
   - En la configuración de Vercel, ve a "Settings > General > Output Directory" y déjalo vacío.
   - En "Settings > General > Root Directory" déjalo vacío o pon "/".
   - Renombra el archivo a `index.html` si deseas que sea la página principal.
4. **Despliega** y accede a la URL generada.

## Permisos y configuración para Vercel

- El repositorio es público y puede ser importado por cualquier cuenta de Vercel.
- No requiere variables de entorno ni configuraciones especiales.
- Si deseas usar un dominio personalizado, configúralo desde el panel de Vercel.

## Créditos

Desarrollado por Grupo Werthein y colaboradores.

---

¡Contribuciones y mejoras son bienvenidas!