# GestorConexionesSsh
Gestiona varias conexiones de ssh

## Descripción del Script `GestionConexionesSsh`

Este script en Bash está diseñado para gestionar múltiples conexiones SSH de forma interactiva, ofreciendo funcionalidades como:

- Verificar si hay conexión a internet.
- Asegurar que el software necesario esté instalado (`ssh`, `fzf`, `gnome-terminal`, etc.).
- Descargar la versión más reciente del script desde GitHub.
- Detectar el emulador de terminal gráfico disponible en el sistema.
- Gestionar una lista de servidores SSH guardados en `~/.ssh_server_list`.
- Generar claves SSH y copiarlas al servidor si no existen.
- Usar `fzf` para seleccionar uno o varios servidores y abrir conexiones en nuevas terminales.
- Ofrecer un menú interactivo con opciones como conectar, agregar, editar, eliminar servidores, hacer backups, restaurarlos, y crear un alias para acceso rápido.

Además, incluye manejo de señales como `Ctrl+C` para salir limpiamente, y está pensado para ser fácil de usar incluso si no se tiene mucha experiencia con Bash.
