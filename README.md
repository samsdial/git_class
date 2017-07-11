Optime Univesity - Git 
===================

Bienvendido a la introducción de Git basico y avanzando aquí el contenido de este curso.

Contenido
-------------

 - Configuración de Git

 ### Glosario de Git
 - Git init
 - Git add
 - Git Commit y git .ignore
 - Git status
 - Git log
 - Git diff
 - Git rm
 - Git reset
 - HEAD en Git

 ### Branching con Git
 - Ramas con Git
 - Comandos del branching
 - Merge en Git
 - Deshacer un Merge
 - Resolver conflictos con Git

 ### Remotos en Git
 
 ### Hostings en Git

 Configuración De Git
-------------
Los primeros paso sera donde disponemos la información y ayudas con el comando man Git en la consola o terminal además este manual se encuentra en el sitio web <a href="https://www.kernel.org/pub/software/scm/git/docs/" target="_blank">Manual page GIT</a>



```sh
git --help
```
Este comando no da toda la información de ayuda para el uso de git y los comando disponibles para usar está herramienta.


```sh
git help init
```
Si necesitamos información puntual sobre un comando escribimos git help + el comando que requerimos saber su documentación.

```sh
git config
```
Nos permite configurar la instalación git o un en un repositorio individual o particular.

```sh
git config -l 
```
Nos permite listar la configuración dentro de la carpeta a trabajar.

```sh
git config --global user.name "NAME USER"
git config --global user.mail sucorreo@miweb.com
```

Nos permite cambiar la configuración de nombre de usuario y el correo electronico, ademas del editor que normalmente usamos.

Glosario de Git
-------------

 ### Git init