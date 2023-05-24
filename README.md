# Paso a paso
1. Después de crear el repositorio en github, se abre el git bash en el escritorio y se utiliza el comando 'git clone https://github.com/egarcia9543/devjumpers.git' para clonar el repositorio que había creado.

2. Una vez clonado, se utiliza el comando 'cd devjumpers/' y 'touch README.md' para crear el archivo readme

3. Después, se utiliza 'git add .' seguido de 'git commit -m "primer commit"' antes de hacer el push al repositorio en la nube

4. Seguidamente, se crean el fichero y la carpeta privado.txt y privada con los comandos 'touch privado.txt' y 'mkdir privada' respectivamente

5. Luego de esto, se utiliza el comando 'touch .gitignore' y se crea el archivo en el cual se ponen los nombres de los elementos que vamos a ignorar, para comprobar que funciona, se hace el proceso de add, commit y push al repositorio en línea para ver que el archivo y la carpeta no fueron subidos a este.

6. Se crea el fichero 1.txt con 'touch 1.txt'

7. Se crea la rama v0.2 con el comando 'git branch v0.2' y nos movemos a ella con 'git checkout v0.2' allí utilizamos el 'touch 2.txt' para crear el archivo y luego hacemos el proceso de add, commit y push para subir los cambios

8. Luego de todo esto, pasamos a la rama main con 'git checkout main' y hacemos el merge de ambas ramas con el comando 'git merge v0.2'