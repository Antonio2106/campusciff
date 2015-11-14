## Antonio Bastidas

### Acciones iniciales

A continuacion agrego los comandos usados:

 * git config --global user.name "Antonio"
 * git config --global user.email "bastidas_ant@hotmail.com"    
 * cd campusciff  ## Ya habia sido creada en clases
 * git init
     
 **Ejercicio 2 Pag 24:**

 1. Ya fue creado previamente en _add repo_ en GitHub
 2. Clonar vuestro repo en local

 Generar una clave SSH - Caso Ubuntu
 * cd ~/.ssh
 * ssh-keygen
 * cat ~/.ssh/id_rsa.pub # Para copiar la clave
 Creacion de carpeta campusciff en local
 * Ya habia sido creada
 * git init # Para inicializar la carpeta
 Clonar el repositorio
 * git clone https://github.com/Antonio2106/campusciff

 3. Crear un archivo Readme.md en el repositorio local
 * touch README.md # dentro de campusciff
 # Verificar que el README.md esta dentro de la segunda carpeta campusciff
 * echo para copiar lo que esta en el .txt a README

 Nota: Algunos comandos hasta ahora
 * git status
 * git add README.md
 * git status # Paso a la zona stage
 * git add campusciff
 * git status
 4. Hacer un commit inicial
 * git commit -m "commit inicial"
 5. Subir los cambios a un repositorio remoto
 * git pull
 * git push https://github.com/Antonio2106/campusciff master
 # Introducir clave y pass

 **Ejercicios 2.4 Pag 10**

 1. Crear un fichero privado.txt
 * touch privado.txt
 2. Crear carpeta privada
 * mkdir privada
 3. Realizar cambios...
 * touch .gitignore
 * cat .gitignore
 * gedit .gitignore  # instalarlo con sudo apt-get install gedit
 # abrirlo y escribir: privado.txt y /privada en la otra linea
 * git add .gitignore
 * git commit -m "Archivo oculto .gitignore creado"
 4. Anadir fichero
 * touch 1.txt
 5. Crear un tag
 * git tag -a v0.1 -m "Etiqueta agregada"
 6. Subir los cambios
 * git add 1.txt
 * git push https://github.com/Antonio2106/campusciff master

 **Ejercicios 2.6 Pag 12**

 1. Crear una rama remota
 * git branch v0.2
 2. Posicionar la carpeta de trabajo
 * git checkout v0.2
 3. Anadir un fichero
 * touch 2.txt
 * git add 2.txt
 * git commit -m "Archivo creado"
 4. Subir los cambios
 * git push https://github.com/Antonio2106/campusciff master
					       
					        

Ver mi [GitHub](https://github.com/Antonio2106)

Repo on GitHub - Master in Big Data - Data Science Toolkit

