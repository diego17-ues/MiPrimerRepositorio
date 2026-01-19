Issue: Configuración SSH en Windows con Git Bash presenta errores por espacios en el nombre de usuario
📌 Descripción

Al intentar configurar autenticación SSH con GitHub en Windows usando Git Bash, se presentan errores al iniciar o usar ssh-agent, especialmente cuando el nombre de usuario del sistema contiene espacios (por ejemplo: DIEGO GONZALEZ).

Esto provoca que comandos como ssh-add no puedan conectarse al agente, aun cuando la llave SSH existe y es válida.