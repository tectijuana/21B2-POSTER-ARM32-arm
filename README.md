![](imagen/portadatcnm.png)

#    Tecnológico Nacional de México
#   Instituto Tecnológico de Tijuana
#        Subdirección Académica
# Departamento de Sistemas y Computación
##  Ingeniería en Sistemas Computacionales
##        LENGUAJES DE INTERFAZ
##   Profesor: MC. René Solis Reyes
##     Semestre sep - ene 2021
----
# Practica Bloque: 📝
# Objetivo:  AUTOMATIZACIÓN USANDO "MAKE" EN TERMINAL
----

# 📝 Apellidos, Nombres y Num Control


-----

📝  Debe crear dos DIRECTORIOS uno  "codigo"  ahi estarán los GIT CLONE, todos los ".s" y otro diga "docs" donde pondrá README.md e imagenes.

Recuerde que para llamar imagenes se pone "! [] (imagenes/foto.png) "    ...(sin comillas ni espacios claro) de debe dejar el README adentro de imagenes ya debe enlazar partes a un README central.


📝  Todo código debe arreglar su ENCABEZADO como lo platicamos en clase.

(puede personalizar esta README.md a su manera presentación profesional)

---

# ¿Como subir a GitHub su trabajo desde el RPI-HOST-NODO-CLIENTE-PC?

# PREPARACION
## 1ra vez en el nodo solamente, actualizar e instalar las herramientas GIT, definir el nombre del programador
```bash

$ sudo apt update
$ sudo apt upgrade
$ sudo apt install git

$ git config --global user.name "NOMBRE AQUI"
$ git config --global user.email "CORREO@tectijuana.edu.mx"

$ git config --global color.ui true  (para hay mas opciones de configuración)
$ git config --global core.editor nano
```

## Clonar el REPO en su cliente (RPI-HOST-NODO-PC) es universal el procedimiento todo OS con Git utilerias instalado.
```bash
$ git clone http://github.com/tectijuana/ELrepositorioTEC (aqui cambiar claro)
$ cd ELrepositorioTEC/code
$ nano practica.s
```

_(Aqui corrige todo lo que debe de hacer, como  gnu-MAKE, etc.)_

# Subirlo a Github via sus CLI (utilerias)

```bash
$ git add .                         (si un punto es decir *.* todo el directorio
$ git commit -m "----AQUI VA UN MENSAJE PUBLICO AL REPO, QUE HIZO, PORQUE,ETC------" (entre comillas)
$ git push --force origin master     (DEBE PEDIR CONTRASEÑA SI HAY CAMBIOS)
```

Y para actualizar o mas bien sincronizar, pues halla modificaciones en GitHub:
```bash
$ git pull
```
_recodemos que todo esto en dentro del directorio clonado del repositorio_

Tig - Un navegador de línea de comandos para repositorios Git
https://es.linux-console.net/?p=358

_(En windows puede que aparecer la ventaja de Git solicitando su login/password, otros sistemas es directo en la terminal)_


