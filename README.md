# Conceptos básicos pre-programación

## Comandos basicos del terminal:

- `pwd`: Me permite conocer la ruta actual (Donde estoy ubicado).

- `ls`: Ver los elementos de la carpeta donde estoy ubicado.

- `clear`: Limpiar la pantalla.

- `ls -la`: Ver detalle de la información con los permisos que tienen esos recursos.

- `mkdir`: Crear un directorio.

- `rm - rf [nombre directorio]`: Borrar de forma forzosa el recurso.

- `cd [carpeta]`: Dirigirme a una carpeta deseada.

- `cd ..`: Devolverme a una ruta o carpeta anterior.

- `touch [NombreNuevoArchivo]`: Crear un archivo de cualquier tipo distinto a una carpeta.

- `nano [NombreNuevoArchivo]`: Crear un archivo.

- `cat [NombreNuevoArchivo]`: Mostrar los datos de un archivo.

## Comandos básicos de git:

- `git config --global user.name <name>`: Define el nombre que se va a utilizar en los commits de forma global (para el usuario actual).

- `git config --global user.email <email>`: Define el correo electrónico que se va a utilizar en los commits de forma global (para el usuario actual).

- `git config --global -e`: Comando para verificar la información de la configuración

- `git init`: este comando se encarga de iniciar el repositorio (esto va a crear una carpeta oculta .git en la carpeta donde ejecutes este comando).

- `git add .`: Prepara los archivos para el commit .

- `git commit -m <descripción de los cambios>`: Crea un commit a partir de los cambios que están en el index con el mensaje que se le pase a la opción -m .

- `git status`: Muestra la lista de archivos con cambios desde el último commit y los que van a ser incluídos en el siguiente commit.

- `git remote add origin <URL repositorio>`: Indicar la dirección del repositorio

- `git push origin <Raman main>`: Entregar los cambios

- `git pull origin <Raman main>`: Bajar los cambios
