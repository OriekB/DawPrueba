# Informe GitHub
## Beniamin Nicolae Posea

_Git_ es un software de codigo abierto usado para el control de versiones en todo tipo de proyectos y _GitHub_ es una de las interfaces web que mantienen repositorios en almacenamiento tipo _nube_.

### Usos
* Permite a varios desarolladores acceder a un proyecto de manera concomitente.
* Hacer un seguimiento de todos los cambios realizados.
* Almacenar _instantáneas_ de un proyecto al que se pueda volver en caso de error.
* Crear _branches_ o ramas para que se pueda trabajar en diferentes funcionalidades.


### Cómo se usa GitHub?

Para empezar se crea una cuenta de usuario en [GitHub](https://github.com/) y se instala _Git_ en el ordenador y apartir del 13/08/21 imperativo crear y usar _tokens_ para identificarse.
Se puede crear un token accediendo a la cuenta de _GitHub_ en _Settings->DeveloperSettings->Personal access tokens_ y puelsando el botón _Generate new token_ se crea con una duración de 30 días.
A este punto se puede crear un repositorio o unirse a otro ya creado. En caso de esto ultimo mediante el comando _clone_ (**git clone _dirección repositorio_**) se puede descargar una copia del proyecto en local para empezar a trabajar.
Una vez realizados cambios estos se guardan con el comando _add_(**git add _nombre archivo/carpeta_**) seguido del comando _commit_(**git commit -m "descripcion"**) que hace una instantánea del proyecto junto a una descripción.
Para guardar el progreso en la nube esta el _push_(**git push**). En caso de conflictos a la hora de subir archivos a la nube, se puede usar _pull_ (**git pull**) esto sirve para actualizar la versión local.
En caso de querer ver todos los _commit_ hechos está el comando _log_ (**git log --oneline**) para ver el historial resumido, gracias al _--omeline_.






## Bibliografía
* [An introduction to GitHub](https://digital.gov/resources/an-introduction-github)
* [Git vs Github: ...](https://kinsta.com/es/base-de-conocimiento/git-vs-github/)
