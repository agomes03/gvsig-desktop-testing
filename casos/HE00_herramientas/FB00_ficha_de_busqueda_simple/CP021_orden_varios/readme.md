## HE00FB00CP021 Ordenar varios campos 

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP021&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargamos el fichero de datos y ordenamos tres campos, en orden ascendente. El orden de los campo sera; en primer lugar "byte", despues "string" y por ultimo "long" El resultado final es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. Añadiremos la capa *.csv*
2. Mostrar la tabla de atributos en la vista
2. Seleccionar menu *Tabla*/Busqueda por atributos
3. Abriremos las herramientas extra del panel de busqueda
4. Seleccionaremos la herramienta "Ordenar por"
5. Utilizamos la barra del filtro para buscar "Long"
6. Pulsaremos en el icono del "filtro de seleccion"
7. Seleccionaremos el campo "long" de la lista de campos
8. Pasaremos el campo seleccionado a la tabla de la derecha con las flechas
9. Repetiremos la misma accion para los campos "byte" y "string"
10. Seleccionaremos el campo "Long" y lo moveremos hasta la tercera posicion con la flecha de bajar los campos 
11. Seleccionaremos el campo "Byte" y lo moveremos hasta la primera posicion con la flecha de subir los campos
12. Pulsaremos el icono de "Orden ascendente"
13. Pulsaremos en el boton "Aceptar"

### Resultados esperados

Como resultado encontraremos los tres campos ordenados con el campo "byte" en primer lugar, seguido del campo "string y por ultimo el campo "long" y en sentido ascendente comenzando por el "ID"= 1 y acabando por el "ID"= 9. 

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion con este test](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP021+Ordenar+varios+campos)
[](readme.md)