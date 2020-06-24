## HE00FB00CP028 Acumular filtros para busquedas de 5 campos

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP028&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargamos el fichero de datos y acumularemos cinco busquedas distintas de cinco campos distintos. El resultado final es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. Añadiremos la capa *.csv*
2. Mostrar la tabla de atributos en la vista
3. Seleccionar menu *Tabla*/Busqueda por atributos
4. Seleccionaremos el campo "String" de la lista de campos
5. Seleccionaremos el operador "Igual a" de la lista de operadores logicos
6. Seleccionaremos el valor "yo1"
7. Escogeremos el operador logico "O" de la lista de operadores logicos
8. Seleccionaremos el segundo campo "ID" de la lista de campos
9. Seleccionaremos el operador "Igual a" de la lista de operadores logicos
10. Seleccionaremos el valor "3"
11. Escogeremos el operador logico "O" de la lista de operadores logicos
12. Seleccionaremos el campo "Byte" de la lista de campo
13. Seleccionaremos el operador "Igual a" de la lista de operadores logicos
14. Seleccionaremos el valor "70"
15. Pulsaremos en el icono de "Acumular filtros"
16. Una vez añadida la condicion pulsaremos en el icono de "ver filtro acumulado"
17. Comprobaremos que la condicion que hemos añadido es correcta
18. Seleccionaremos el campo "long" de la lista de campos
19. Seleccionaremos el operador "Igual a" de la lista de operadores logicos
20. Seleccionaremos el valor "1000"
21. Escogeremos el operador logico "Y" de la lista de operadores logicos
22. Seleccionaremos el campo "Decimal" de la lista de campos
23. Seleccionaremos el operador "Igual a" de la lista de operadores logicos
24. Seleccionaremos el valor "456.123"
25. Pulsaremos en el icono de "Acumular filtros"
26. Una vez añadida la condicion pulsaremos en el icono de "ver filtro acumulado"
27. Volveremos a comprobar que la expresion final es correcta
28. Pulsaremos en el boton "Aceptar"
29. Pulsaremos en el boton "Buscar"
30. Pulsaremos el icono de "Eliminar el filtro acumulado"



### Resultados esperados

- Como resultado del paso 15 y se habilitara la pestaña de "Acumular filtros" y se limpiaran los valores de los campos.

- Como resutado del paso 16 se habilitara la pestaña "ver filtro acumulado" y obtendremos la expresion ((("FB00_datos1 (4)"."String" = 'yo1') OR ("FB00_datos1 (4)"."ID" = 3)) OR ("FB00_datos1 (4)"."Byte" = 70)).

- Como resultado del paso 25 se habilitara la pestaña de "Acumular filtros" y se limpiaran los valores de los campos.

- Como resultado del paso 26 se habilitara la pestaña "ver filtro acumulado" y obtendremos la expresion final ( ("FB00_datos1 (4)"."String" = 'yo1') OR ("FB00_datos1 (4)"."ID" = 3) OR ("FB00_datos1 (4)"."Byte" = 70)) AND 
( (("FB00_datos1 (4)"."Long" = 1000) AND ("FB00_datos1 (4)"."Decimal" = 456.123))).

- Como resultado de la busqueda del paso 29 obtendremos 1 resultado con el "ID" = 1.

- Como resultado del paso 30 se nos eliminaran todas las condiciones que habiamos acumulado

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion con este test](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP028+Acumular+filtros+para+busquedas+de+5+campos)
[](readme.md)