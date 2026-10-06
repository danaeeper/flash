# FlashBox — iOS

App iOS nativa para abrir juegos Flash `.swf` usando Ruffle WebAssembly localmente.

## Importante
Este proyecto es una base compilable, no un IPA firmado. El entorno donde se generó no dispone de Xcode/macOS, por lo que no se fabrica un binario iOS falso.

## Preparar Ruffle
1. En un Mac con Xcode, ejecuta `./Scripts/fetch_ruffle.sh`.
2. El script descarga el paquete `web-selfhosted` del release nightly más reciente de Ruffle y lo coloca en `FlashBox/Resources/Ruffle/ruffle/`.
3. Abre `FlashBox.xcodeproj` en Xcode.
4. Añade la carpeta `FlashBox/Resources/Ruffle` al target asegurando "Copy items if needed" y "Create folder references".
5. Selecciona tu iPhone y compila/firma.

Ruffle es el motor Flash; soporta ActionScript 1, 2 y 3 en buena medida, aunque su propia documentación indica que todavía está en desarrollo.
