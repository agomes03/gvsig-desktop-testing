## HE00FB00CP028 Acumular filtros

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP028&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargamos el fichero de datos y acumularemos distintas busquedas de distintos campos. El resultado final es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. Añadiremos la capa *.csv*
2. Mostrar la tabla de atributos en la vista
3. Seleccionar menu *Tabla*/Busqueda por atributos
4. Seleccionaremos el campo "String" de la lista de campos
5. Seleccionaremos el valor "yo1"
6. Escogeremos el operador logico "O" de la lista de operadores logicos
7. Seleccionaremos el segundo campo "ID" de la lista de campos
8. Seleccionaremos el valor "3"
9. Seleccionaremos el operador "Igual a" de la lista de operadores logicos para los dos campos
10. Pulsaremos en el boton "Buscar"
11. Pulsaremos en el icono de "Acumular filtros"
12. Una vez añadida la condicion pulsaremos en el icono de "ver filtro acumulado"
13. Comprobaremos que la condicion que hemos añadido es correcta
14. Pulsaremos en el boton "Aceptar"
15. Seleccionaremos el campo "byte" de la lista de campos
16. Seleccionaremos el valor "20"
17. Seleccionaremos el operador "Igual a" de la lista de operadores logicos
18. Pulsaremos en el boton "Buscar"
19. Pulsaremos en el icono de "Acumular filtros"
20. Una vez añadida la condicion pulsaremos en el icono de "ver filtro acumulado"
21. Volveremos a comprobar que la expresion final es correcta
22. Pulsaremos en el boton "Aceptar"
23. Pulsaremos el icono de "Eliminar el filtro acumulado"



### Resultados esperados

- Como resultado de la busqueda del paso 10 obtendremos 2 resultados con el "ID" = 1 e "ID" = 3

- Como resutado del paso 14 obtenemos la expresion (("FB00_datos1 (4)"."String" = 'yo1') OR ("FB00_datos1 (4)"."ID" = 3))

- Como resultado de la busqueda del paso 18 obtendremos 1 resultado con el "ID" = 2

- Como resultado del paso 22 obtenemos la expresion final ( ("FB00_datos1 (4)"."String" = 'yo1') OR ("FB00_datos1 (4)"."ID" = 3)) AND 
( ("FB00_datos1 (4)"."Byte" = 20))

- Como resultado final del paso 23 se nos habran eliminado todas las buquedas que habiamos acumulado del icono de acumulacion de filtros

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion con este test](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP028+Acumular+filtros)
[](readme.md)