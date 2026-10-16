# CRONET Screen Recorder

Grabador personal para Windows x64. Este repositorio distribuye instaladores y avisos de actualización; no contiene grabaciones ni ajustes personales.

## Instalar

Descarga el instalador `.exe` desde [la última versión](https://github.com/cronetegm-cpu/CRONET-Screen-Recorder-Releases/releases/latest).

Si tienes la versión 0.3.0, instala la 0.4.0 manualmente una vez. Desde 0.4.0 puedes buscar nuevas versiones en **Ajustes > Actualizaciones**, o dejar activada la consulta al abrir la app. No necesitas una cuenta de GitHub para actualizar.

La app pide aceptar la descarga y abre el instalador cuando no hay grabaciones ni procesamiento en curso. Tus archivos y preferencias permanecen en tu equipo. Se comprueba la firma del aviso y el SHA256 de la descarga. El ejecutable todavía no tiene firma Authenticode; Windows puede mostrar SmartScreen.

## Versiones

Los archivos de cada release incluyen el instalador, `update.json` firmado y los avisos de dependencias. La publicación de nuevas versiones se realiza después de las pruebas; editar el proyecto no publica automáticamente.

## Dependencias

Incluye FFmpeg/ffprobe (compilación GPL de BtbN), NAudio y .NET. Consulta NOTICE.txt en cada release y los textos de licencia incluidos en la instalación.