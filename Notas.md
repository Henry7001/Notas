# Git y otros sistemas para el control de versiones

## Instalación y configuraciones iniciales

### Windows
1. Descarga e instala Git desde https://git-scm.com/download/win
2. Configura tu nombre de usuario y correo electrónico en Git usando los siguientes comandos en Git Bash o en la terminal:
    - `git config --global user.name "Tu nombre de usuario"`
    - `git config --global user.email "tu correo electrónico"`

### Linux
1. Instala Git usando el gestor de paquetes de tu distribución, por ejemplo:
    - Debian/Ubuntu: `sudo apt-get install git`
    - Fedora: `sudo dnf install git`
    - Arch Linux: `sudo pacman -S git`
2. Configura tu nombre de usuario y correo electrónico en Git usando los siguientes comandos en la terminal:
    - `git config --global user.name "Tu nombre de usuario"`
    - `git config --global user.email "tu correo electrónico"`

### macOS
1. Instala Git a través de Homebrew o descargando el instalador desde https://git-scm.com/download/mac.
2. Configura tu nombre de usuario y correo electrónico en Git usando los siguientes comandos en la terminal:
    - `git config --global user.name "Tu nombre de usuario"`
    - `git config --global user.email "tu correo electrónico"`

## Áreas de trabajo

1. El área de trabajo (working directory) es el directorio de tu proyecto donde trabajas y realizas cambios en tus archivos.
2. Los cambios que realizas en el área de trabajo no se registran automáticamente en Git.

## Restablecimiento de cambios

1. Puedes restablecer los cambios en tu área de trabajo usando el comando `git checkout` seguido del nombre del archivo.
2. Si quieres restablecer todos los cambios en tu área de trabajo a la última versión en Git, utiliza el comando `git checkout .` (el punto al final indica todos los archivos).