# Arduino

> [Arduino][1] es una plataforma de software y hardware libre, basada en una placa con un microcontrolador y un entorno de desarrollo, diseñada para facilitar el uso de la electrónica en proyectos multidisciplinares.


## Instalar Arduino

La descarga de Arduino 3 ocupa 112Mb aproximadamente. Al ser un lenguaje multiplataforma, dependiendo del sistema operativo utilizado deberás seguir unos pasos.


### Windows

1. Accede al apartado de [descargas][2] en la página oficial de Arduino.
2. Descarga Arduino dependiendo de si tu Sistema Operativo es de 32-bit o 64-bit.
    - Inicio / Ejecutar -> ``msinfo32.exe``.
    - Busca una línea que dice ``Equipo basado en``.
        - Si está basado en ``x86`` es de 32 bits.
        - Si está basado en ``x64`` es de 64 bits.
    - En caso de no disponer de privilegios como administrador descarga el archivo ``Windows ZIP file for non admin install``.
3. Descomprime el archivo con extensión ``.zip``.
4. Una vez descomprimido haz clic en ``arduino.exe``.


### Mac OS X

1. Accede al apartado de [descargas][2] en la página oficial de Arduino.
2. Descarga Arduino dependiendo de si tu Sistema Operativo es de 32-bit o 64-bit.
    - En la terminal ejecutar -> ``uname -a``.
    - Fíjate en la línea que aparece:
        - Si aparece ``RELEASE i386`` es de 32 bits.
        - Si aparece ``RELEASE x86_64`` es de 64 bits.
3. Descomprime el archivo con extensión ``.zip`` y arrástralo en la carpeta ``/Aplicaciones``.
4. Una vez descomprimido haz clic en ``arduino.app`` y sigue los pasos del asistente.


### Linux

1. Accede al apartado de [descargas][2] en la página oficial de Arduino.
2. Descarga Arduino dependiendo de si tu Sistema Operativo es de 32-bit o 64-bit.
    - En la terminal ejecutar -> ``uname -a``.
    - Fíjate en la línea que aparece:
        - Si aparece ``i386, i486, i586 o i686`` es de 32 bits.
        - Si aparece ``x86_64`` es de 64 bits.
3. Una vez descargado descomprímelo en tu directorio local. Puedes seguir los pasos en la web de [Arduino][3].
4. Una vez descomprimido se habrá creado una carpeta llamada arduino-1.8.7 o similar. 
5. Accede al directorio descoprimido con ``cd arduino-xxxx`` y ejecuta el instalador con ``./install.sh``



[1]: https://www.arduino.cc/
[2]: https://www.arduino.cc/en/Main/Software
[3]: https://www.arduino.cc/en/Guide/Linux/
