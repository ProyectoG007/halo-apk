# HALO · builds de prueba para Android

Acá vive solo el APK para instalar y probar la app. El código fuente está en un
repositorio privado aparte.

## Descargar

**[HALO.apk](https://github.com/ProyectoG007/halo-apk/raw/main/HALO.apk)** — 28 MB

## Instalar

1. **Desinstalá la versión anterior de HALO** si ya la tenés. Está firmada con
   otra clave y Android rechaza instalarla encima ("App no instalada").
2. Abrí el archivo descargado. Android va a pedir permiso para instalar apps de
   origen desconocido: aceptalo.

Es la versión para celulares con procesador arm64, que es prácticamente
cualquier Android de los últimos años.

## Qué hay que saber

- La app se conecta a un servidor de prueba gratuito que **se duerme a los 15
  minutos sin uso**. El primer ingreso puede tardar cerca de un minuto: si da
  error de conexión, esperá y probá de nuevo.
- La base de datos es **descartable**: cada vez que el servidor se reinicia se
  borra todo y se vuelve a crear el catálogo. Lo que cargues durante una prueba
  se pierde.
- Las notificaciones push están apagadas, falta configurarlas.
