# Pausa: Clásicos · actualizaciones

Este repositorio solo guarda lo que el juego descarga para actualizarse. El
código está en el repositorio privado del juego.

- `version.json`: la última versión, sus novedades y qué archivo bajar.
- `paquetes/VERSION.pck`: los cambios de esa versión. El juego lo baja con el
  botón **Actualizar** y lo carga al reiniciar.
- `Pausa-Clasicos.apk`: el APK más reciente, para instalarlo por primera vez o
  cuando una versión no se puede instalar con un paquete.

Se arma con `tools/publicar_actualizacion.py` del repositorio del juego; no
editar a mano.
