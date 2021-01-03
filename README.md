# Instrucciones para clonar el repositorio desde github

* Copiar en el portapapeles la url del repositorio remoto:

* _https://github.com/aldocape/repo-diplomatura.git_

* Abrimos un __terminal__
* Nos posicionamos en un directorio en el cual queramos tener nuestro proyecto, es decir, establecer un sistema de control de versiones (donde estemos parados, git nos creará un directorio que se llame igual que el proyecto que vamos a clonar)

* Ejemplo: `mkdir proyectos`
         
* Nos metemos en el directorio ejecutando en el terminal el comando: `cd proyectos`

* Una vez que decidimos que éste será el directorio a utilizar, procedemos a clonar el repositorio:

* Ejecutar el comando git clone, y pegar como parámetro la url copiada, lo que nos deja el texto siguiente:

  `git clone https://github.com/aldocape/repo-diplomatura.git`
  
Cabe mencionar que el proceso no solicitará password, debido a que el repositorio es público

El comando arrojará la salida:

Cloning into 'nombre-del-repo-en-la-nube'  
remote: Enumerating objects: 9, done.  
remote: Counting objects: 100% (9/9), done.  
remote: Compressing objects: 100% (8/8), done.  
remote: Total 9 (delta 1), reused 9 (delta 1), pack reused 0  
Unpacking objects: 100% (9/9),942,67 KiB | 698.00 KiB/s, done.  
  
O similar.

