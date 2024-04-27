
# Delete Metadata Bash Script

## Descripción

Este script en Bash te permite eliminar los metadatos de imágenes utilizando la herramienta ExifTool. Los metadatos son información adicional almacenada en archivos de imagen que puede incluir detalles como la ubicación, la fecha y la cámara utilizada para tomar la imagen. Este script es útil si deseas eliminar metadatos sensibles antes de compartir o publicar imágenes en línea.

## Uso

1. Asegúrate de tener ExifTool instalado en tu sistema. Si no está instalado, el script intentará instalarlo automáticamente utilizando `apt-get` en sistemas basados en Debian.

2. Ejecuta el script proporcionando las rutas y nombres de las imágenes como argumentos separados por espacios. Por ejemplo:

```bash
./delete_metadata.sh /ruta/a/imagen1.jpg /ruta/b/imagen2.jpg
```
3. El script mostrará los metadatos de cada imagen y te preguntará si deseas borrarlos.
4. Si eliges borrar los metadatos, el script los eliminará de la imagen seleccionada.

## Requisitos
. Linux (el script se ha probado en sistemas basados en Debian)
. ExifTool (se instalará automáticamente si no está presente)

## Instrucciones de Instalación

1. Clona este repositorio en tu máquina local:

```bash
git clone https://github.com/Sr-Mxr/metadel.git
```
2. Navega al directorio del repositorio:
```bash
cd delete-metadata-bash-script
```
Ejecuta el script según las instrucciones anteriores.

## Contribución
Si encuentras algún error o tienes alguna sugerencia para mejorar el script, no dudes en abrir un problema o enviar una solicitud de extracción.

## Autor
Este script fue creado por mxr.

## Licencia
Este proyecto está bajo la Licencia MIT.







