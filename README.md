# gpsvuelo-releases

Solo binarios de firmware compilados (`.bin`) para las actualizaciones OTA
del [GPS de Vuelo](https://github.com/albafer/gpsvuelo) (M5Stack Core2).
No hay código fuente aquí — lo publica automáticamente GitHub Actions desde
el repo privado en cada cambio del sketch.

- `version.txt`: el hash corto del último commit compilado (lo que compara
  el propio equipo para saber si hay algo nuevo).
- Cada versión se publica como [Release](../../releases), con el `.bin`
  adjunto.
