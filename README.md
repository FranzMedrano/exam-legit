# Curso GIT desde cero
Sistema de Control de Versiones para el mantenimiento eficiente y confiable de archivos.
## Zonas de GIT
1. Directorio de trabajo.
2. Área de preparación.
3. Directorio GIT.
## Flujo de trabajo básico en GIT
1. Modificas una serie de archivos en tu directorio de trabajo.
## Configurando GIT por primera vez
```
git config --global user.name "Jhon Doe".
```
## Aportes desde otra cuenta
Este texto fue aportado desde la cuenta desde mi cuenta franz medrano.

## Configuración  SHH en windows
1. Creamos una carpeta llama `llaves-ssh` en el disco `C` para evitar de rutas.
2. Ejecutamos el comando `shh-keygen -t rsa -C "mi-correo"`. 
3. El correo debe ser el mismo con el que nos registramos en github para evitar problemas.
Dejamos el passphrase vacío y damos enter.
Cuando nos puda la ruta escribimos `Users/franz/.shh/id_rsa`.
4. Iniciamos ssh-agent en background ejecutando el comando `eval ${ssh-agent -s}`.
5. Agregamos la llave ssh generada a ssh-agent ejecutando el comando `ssh-add /Users/franz/.shh/id_rsa`
6. Ahora podemos hacer pull y push sin cuentas de autorización.