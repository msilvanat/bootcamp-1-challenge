 # Información
          Este es el resultado de mi esfuerzo aprendiendo GIT
 # Por qué el archivo historia.log no apareció?
RESPUESTA: El archivo historia.log no apareció porque el mismo no fue añadido (con el comando git add) a la etapa stage, por lo tanto nunca fue comprometido (commited).
El sólo hecho de que el mismo haya estado en el archivo .gitignore no significa que no vaya a aparecer, ya que
si hubiesemos hecho commit del archivo primero y después agregado a .gitignore, al hacer git checkout -- si hubiera aparecido.
El archivo historia.log no había sido parte de algún commit, por ende no se restauró.