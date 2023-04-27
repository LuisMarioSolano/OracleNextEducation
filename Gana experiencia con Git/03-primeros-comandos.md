# Primeros comandos de Git

## Configuración inicial
Antes de empezar a utilizar Git, es recomendable que realices algunas configuraciones iniciales:

### **Verificar versión**
Para saber que versión de git tienes instalada, debes usar el siguiente comando:

``git --version``

<br>

### **Configuración de usuario**
Debes configurar el nombre y el correo electrónico que utilizarás para tus commits. Utiliza los siguientes comandos, sustituyendo "nombre de usuario" y "correo electrónico" por tus datos:

``git config --global user.name "nombre de usuario"``

``git config --global user.email "corre@electrónico"``

<br>

### **Establecer VS Code como editor (recomendado)**
Una opcion recomendada es establecer el IDE VS Code como editor predeterminado con el siguiente comando:

``git config --global core.editor "code --wait"``
<br>

## Configurar saltos de linea segun el sistema.
Cada sistema tiene su propia forma de interpretar saltos de linea, por ello se busca establecer una configuracion standar dependiendo del sistema usado para la manipulación de archivos.

### Windows:
`` git config --global core.autocrlf true ``

### Linux y Mac:
`` git config --global core.autocrlf input ``
<br>

### **Consultar los datos de usuario**
Para consultar los datos puedes usar el siguiente comando:

``git config --global -e``

<br>

## Crear un repositorio

Un repositorio de Git es un lugar donde se almacenan los archivos y las versiones de los mismos. Para crear un nuevo repositorio, utiliza el siguiente comando en el directorio donde quieres crearlo:

``git init``

<br>
<br>

## Hacer cambios y hacer commits
Después de crear un repositorio, debes hacer cambios en los archivos y guardarlos en el historial de versiones de Git. Estos son los comandos que necesitas conocer:

### **Verificar el estado del repositorio**
Puedes ver el estado actual del repositorio utilizando el comando:

``git status``

<br>

### **Agregar archivos al área de preparación**
Antes de hacer un commit, debes agregar los archivos que quieres incluir en el mismo al área de preparación. Puedes hacerlo utilizando el comando:

``git add nombre-del-archivo``

También puedes agregar todos los archivos modificados en el directorio actual utilizando el comando:

``git add .``

También puedes agregar todos los archivos con una misma extensión modificados en el directorio actual con el comando:

``git add *.nombre-extension``

También puedes agregar todos los archivos dentro de una carpeta modificados en el directorio actual con el comando:

``git add nombre-carpeta/``

<br>

### **Hacer un commit**
Después de agregar los archivos al área de preparación, debes hacer un commit para guardar los cambios en el historial de versiones. Utiliza el siguiente comando:

``git commit -m "mensaje-del-commit"``

<br>

### **Ver historial de commits**
Puedes ver el historial de commits utilizando el comando:

``git log``

<br>
<br>

## Trabajar con ramas
Las ramas son una característica importante de Git que te permiten trabajar en diferentes versiones de un mismo proyecto de manera independiente. Estos son los comandos que necesitas conocer:

### **Crear una rama**
Para crear una rama nueva, utiliza el siguiente comando:

``git branch nombre-de-la-rama``

<br>

### **Cambiar de rama**
Para cambiar de una rama a otra, utiliza el siguiente comando:

``git checkout nombre-de-la-rama``

<br>

### **Fusionar ramas**
Para fusionar una rama con otra, utiliza el siguiente comando:

``git merge nombre-de-la-rama``

<br>
<br>

## Conclusiones
Estos son solo algunos de los primeros comandos que deberías conocer al empezar a trabajar con Git. A medida que vayas utilizando esta herramienta, descubrirás muchas otras características interesantes que te ayudarán a trabajar de manera más eficiente

[Regresar](README.md)







