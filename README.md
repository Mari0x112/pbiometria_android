# pbiometria_android
### Descripción:
Reposotorio para el código JAVA de Android del proyecto.
### Instrucciones de uso:
- **1.** Descargar y extrar el .zip del repositorio.
- **2.** Descargar e instalar [Android Studio](https://developer.android.com/studio).

- **3.** Una vez iniciado Andoid Studio, extraer el archivo "AndroidBluetooth.zip" en cualquier directorio y abrir el proyecto. 
- **4.** Al abrirlo, acceder al archivo "MedicionHandler" y sustituir dentro de la variable "url" la direccion IP escrita por la direccion IPV4 del ordenador en uso. Para cononcer la direccion IPV4 del ordenador: 
    - Windows: Win+R --> cmd --> ipconfig (IPV4)
    - Linux / Mac OS: Ctrl+Alt+T -> ifconfig (inet)

- **5.** Finalizado el cambio, guardar el archivo y conectar un móvil Android para instalar la aplicación. Hay que tener en cuenta que la depuración por USB del dispositivo tiene que estar activa, además de permitir la transferencia de archivos al conectarlo. 

- **6.** Al conectar el dispositivo Android, ejecutar la aplicación desde Android Studio para que se instale. Finalizada la instalación y con la aplicación en pantalla, pulsar primeramente en "Buscar mi dispositivo BTLE", y una vez aparezca el mensaje de "Escuchando dispositivo GTI-3A-Laura", pulsar en el botón "Publicar medición" para registrar una nueva medición.

*Nota: Al desarrollar la aplicación no todos los dispositivos fueron capaces de detectar los beacons emitidos por el sensor. Si no se muestran valores una vez pulsado el botón de publicar, puede que éste sea su caso. Es posible que su dispositivo no pueda detectar beacons BTLE (Bluetooth Low Energy) y necesite de otro más moderno.*

#### Recuerde, el orden a seguir para implementar el proyecto es:
- [Arduino](https://github.com/Mari0x112/pbiometria_arduino) --> [Web](https://github.com/Mari0x112/pbiometria_web) --> [Android](https://github.com/Mari0x112/pbiometria_android)
