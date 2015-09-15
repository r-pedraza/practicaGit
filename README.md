
#Raúl Pedraza León
>>## PracticaGit


###11</br>Se utiliza git reste HEAD~1 para mover el puntero HEAD un paso por detrás de los cambios realizados. si hacemos un git status podremos deshacer los cambios con git checkout — poem.md    para deshacer los cambios por completo.

###12</br>git reflog   buscamos el momento en que s ehan realizado los cambios de sustituir red y blue, hacemos un checkout a 378775c creo una nueva rama llamada rehacer realizo un checkout a htmlify y mergeo rehacer con htmlify, ya tengo los cambios anteriores en htmlify.

###13</br>En mi caso no. Nuestra rama esta mas actualizada que master, es decir, tiene lo de master y mas contenido, de ahí que no cree conflicto.

###19</br>Si se intenta hacer desde la rama matrix el mere en dirección htmlify si da conflicto por que para realizar por que se han modificado las mismas lineas.

###</br>25</br>En mi caso no, en el merge anterior tuve que solucionar los conflictos y una vez resueltos no ha dado conflictos.

###</br>25</br>git log —graph —decorate —pretty=0
###26</br>git merge -no-ff title    Podría ser Fast Forward por que podríamos poner todos los comió en una línea y el grafo serviría igualmente.

###27</br>git reset HEAD~1  

###28</br>git checkout — poem.md
###29 </br>git branch -D title

32 git reflog       git checkout 825be7b
33 git reflog       git checkout 648227b
