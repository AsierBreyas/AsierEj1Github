# Ejercicio Git y GitHub
De manera individual
1. Crea un repositorio con el nombre NOMBREEjGithub1
    - mkdir AsierEj1GitHub
2. Añade un README.md al repositorio con una pequeña descripción diciendo que este
es el primer ejercicio de práctica de este repositorio
    - echo "# Este es el mensaje predefinido que tengo que poner, por favor sacame de venezuela"> Leeme.md
3. Descarga el repositorio de Github
    - git remote add origin https://github.com/AsierBreyas/AsierEj1Github.git
    - git push -u origin master
4. Añade un fichero ciudades.txt que incluya “Irun” como texto.
    - echo "Irun" > cuidades.txt
5. Haz un commit con este cambio.
    - git commit -m "Irun añadido a cuidades.txt"
6. Añade “Donosti” al fichero ciudades.txt
    - Echo Donosti >> cuidades.txt
7. Haz otro commit con estos cambios.
    -git commit -m "Donosti añadido"
8. Envía todos estos cambios a GitHub y comprueba que se han cambiado
correctamente.
    -git push
9. Añade “Renteria” al fichero de ciudades.txt
    - git echo >> Renteria
10. Haz un commit con este cambio.
    - git commit -m "Renteria añadido"
11. Añade (Desde la interfaz de GitHub) “Hondarribia” al fihcero ciudades.txt y haz el
commit correspondiente
12. Piensa qué habría que hacer ahora para poder juntar los cambios que tenemos en
nuestro git local y el proyecto que tenemos en GitHub.
    - Git Pull
13. Realiza los cambios necesarios para poder arreglar esto y tener ambos cambios en el
.git local y el GitHub
14. Añade otro fichero ciudadesCanada.txt que incluya “Ottawa”, “Vancouver” y
“Toronto”.
    - echo Ottawa Vancouver Toronto > cuidadesCanada.txt
15. Haz un nuevo commit con estos cambios con el mensaje “Nuevo fichero ciudades
Alemania”.
    git commit -m "Nuevo fichero ciudades Alemania”
16. Cambia el nombre al último commit y añádele el mensaje “Nuevo fichero ciudades
alemania”.
17. Sube los cambios realizados hasta ahora a GitHub .
18. Añade las ciudad “Calgary” a ciudadesCanada.txt y haz commit.
19. Añade la ciudad “Montreal” a ciudadesCanada.txt y haz commit.
20. Añade la ciudad “Edmonton” a ciudadesCanada.txt y haz commit.
21. Añade la ciudad “Quebec” a ciudadesCanada.txt y haz commit.
22. Haz un git reset --soft al commit de añadir la ciudad Edmonton. Piensa si este cambio
puede ser reversible, y si es así, hazlo.
23. Haz un git reset --mixed al commit de añadir la ciudad Montreal. Piensa si este cambio
puede ser reversible, y si es así, hazlo.
24. Haz un git reset –hard al commit de añadir la ciudad de Calgary. Piensa si este cambio
puede ser reversible, y si es así, hazlo.
25. Entiende la diferencia que hay al hacer reset entre --soft, --mixed y --hard.