![Command Line Preview](https://raw.githubusercontent.com/breatheco-de/exercise-terminal-challenge/master/preview.png)

This command line challenge is designed to help you become familiar with the bash/command line. The challenge goes over the most used commands every developer needs to know in order to succeed in real life.

> :exclamation: We strongly recommend reading [The Command Line lesson](https://content.breatheco.de/en/lesson/the-command-line-the-terminal) on the BreatheCode platform.

💻The challenge is built for computers using the Linux bash. Use [Gitpod](https://gitpod.io) if you need a terminal in the cloud. 

## 🌱  How to start this project

### 👩‍🎓Students and Teachers must follow this step:

This project comes with the necessary files to start working, but you have two options to start:

a) Open this link in your browser to clone it with gitpod (recommended): https://gitpod.io#https://github.com/breatheco-de/exercise-terminal-challenge.git

b) You can clone this repository on your local computer:

```sh
$ git https://github.com/breatheco-de/excercise-terminal-challenge.git
```

💡 Important: Remember to create a new repository, update the remote (`git remote set-url origin <your new url>`), and upload the code to your new repository using `add`, `commit` and `push`.

## Only teachers must follow this step:

#### 1) Install the packages.

```sh
$ npm install
```

#### 2) Run the presentation.

```sh
$ npm run start
```

# Start Playing!

Follow the presentation for better experience.



EXPLICACIÓN:
*Para poder visualizarlo si no se ejecuta; habría que seguir los pasos 1) y 2) de arriba ^

Después de clonar el respositorio, empecé a seguir los pasos del ejercicio en la terminal. Esto es lo que escribí en cada caso:

·cd thecmdchallenge
·pwd
·ls -a 
·ls -R
·clear
·cd small-name 
como esta carpeta contiene varias, lo que hice fue escribir 'ls' para que me saliera el nombre de la siguiente carpeta; luego accedía a esa carpeta del mismo modo, escribiendo 'cd (y el nombre de la carpeta) y luego volvía a usar ls para ver el nombre de la siguiente carpeta y accedía a ella; y así hasta llegar a la última donde ya aparecía 'trophy.txt'. Para imprimir su contenido escribí: ·cat trophy.txt
Luego continúe con el siguiente paso del ejercicio.

En este caso había que moverse al directorio funcode; entonces tenía que salir de la carpeta small-name y regresar a la carpeta thecmdchallenge (que es la que contenía 'funcode'). Para hacer eso utilicé:
·cd ../.. 
tantas veces como carpetas había hasta llegar a thecmdchallenge.

Luego ya pude acceder a 'funcode' usando el comando 'cd'; y mostré sus archivos usando el comando 'ls'.

Luego entré a la carpeta señalada en el ejercicio y para crear dentro de ella el nuevo directorio usé el comando 'mkdir'.

Para llegar hasta la carpeta boringfolder usé el mismo comando que antes: cd ../.. tantas veces como carpetas hubiera hasta llegar a la carpeta que la contenía (the cmdchallenge). Después accedí a ella usando 'cd' y para saber exactamente dónde se contenía 'the-mostboring-text.txt' usé el comando 'find' ($ find / -name the-mostboring-text.txt), luego copié el resultado y lo usé con el comando 'cd' para llegar hasta 'the-mostboring-text.txt'. Y ya en la la última carpeta que contenía 'the-mostboring-text.txt' use el comando 'cp' para copiar su contenido y crear la nueva carpeta ($ cp the-mostboring-text.txt lol.txt)

Igual que hice antes con 'cd ../..' regresé a la carpeta 'thecmdchallenge' y desde allí usé el comando 'mv' para cambiar lo que pedía el ejercicio ($ mv funcode/kids.jpg funcode/images/hello).

Para eliminar el directorio small-name usé el comando 'rm -r' ($ rm -r small-name/)

En el siguiente paso, utilicé el comando 'find' para encontrar el archivo 'the-ultimate-joke.txt'; accedí a la carpeta que lo contenía con el comando 'cd' y luego imprimí su contenido con el comando 'cat'.

Regresé a 'thecmdchallenge' usando 'cd ../..' y accedí a 'boringfolder' con el comando 'cd'. Y para eliminar su contenido usé 'rm -r' para el directorio 'event-more-boring' y luego usé el comando 'rm' seguido de todos los nombres de los archivos que quedaban dentro de esa carpeta.

Retrocedí a 'thecmdchallenge' con el comando 'cd ../'. Luego abrí el editor de texto VI, escribiendo:
· vi kamehameha/dragon-ball-jokes.md 
para poder editar el archivo pulsé la tecla 'i' y borré lo que pedía el ejercicio y luego usé la tecla 'esc' para salir del modo de edición del archivo. Por último para guardar los cambios escribí ':w' y para regresar a la terminal escribí ':q'.











