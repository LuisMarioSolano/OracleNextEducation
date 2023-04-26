# Cómo instalar Git en Windows y Mac
Git es una herramienta de control de versiones distribuido que se utiliza para rastrear cambios en archivos y coordinar el trabajo en equipos de desarrollo de software. Aquí te presento los pasos para instalar Git en Windows y Mac.

## Windows
1. Descarga el instalador de Git para Windows desde [aquí](https://git-scm.com/download/win).
2. Ejecuta el archivo descargado para iniciar el instalador.
3. Sigue las instrucciones del instalador para instalar Git en tu sistema.
4. En el paso "Adjusting your PATH environment", asegúrate de seleccionar la opción "Use Git from the Windows Command Prompt".
5. En el paso "Choosing the default editor used by Git", selecciona tu editor de código preferido.
6. Haz clic en "Next" para continuar.
7. En el paso "Configuring the line ending conversions", selecciona "Checkout as-is, commit Unix-style line endings".
8. Haz clic en "Next" para continuar.
9. En el paso "Configuring the terminal emulator to use with Git Bash", selecciona "Use MinTTY".
10. Haz clic en "Next" para continuar.
11. En el paso "Configuring extra options", asegúrate de seleccionar la opción "Enable file system caching".
12. Haz clic en "Install" para comenzar la instalación.
13. Espera a que se complete la instalación y haz clic en "Finish" para salir del instalador.
14. Abre la línea de comandos de Windows y ejecuta el comando ``git --version`` para verificar que Git se ha instalado correctamente.

## Mac

1. Abre una terminal en tu Mac.

2. Instala Homebrew si no lo has hecho ya. Puedes instalar Homebrew con el siguiente comando:

    ``/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"``

3. Una vez que Homebrew esté instalado, ejecuta el siguiente comando para instalar Git:

    ``brew install git``

4. Espera a que se complete la instalación.

5. Verifica que Git se haya instalado correctamente ejecutando el comando 

    ``git --version``.

En resumen, la instalación de Git en Windows y Mac es bastante sencilla y solo requiere seguir unos pocos pasos. En Windows, debes descargar el instalador y seguir las instrucciones del instalador. En Mac, debes instalar Homebrew y luego usarlo para instalar Git. Una vez que hayas instalado Git, podrás comenzar a utilizarlo para controlar el historial de cambios en tus archivos y colaborar de manera eficiente en equipo.

[Regresar](README.md)