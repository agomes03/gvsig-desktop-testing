## HE00FB00CP017 Añadir a marcadores 

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP017&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargamos el fichero de datos y realizamos una busqueda. Dicha busqueda añadiremos a marcadores para posteriormente modificarlo de forma correcta. El resultado final es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. Añadiremos la capa *.csv*
2. Mostrar la tabla de atributos en la vista
3. Seleccionar menu *Tabla*/Busqueda por atributos
4. Seleccionaremos el campo "ID" de la lista de campos
5. Seleccionaremos el operador "Igual a" de la lista de operadores logicos
6. Seleccionaremos el valor "2"
7. Pulsaremos en el boton "Añadir a marcadores"
8. Seleccionaremos el marcador que nos ha creado
9. Pulsaremos en el boton "Modify"
10. Modificaremos el nombre del marcador de "2020-06-16 18:35 ("FB00_datos1 (2)"."ID" = 2)" a "("ID" = 2)"
11. Pulsaremos en el boton "Aceptar"


### Resultados esperados

- Como resultado del paso 7 obtendremos el parametro "2020-06-16 18:35 ("FB00_datos1 (2)"."ID" = 2)" añadido a marcadores

- Como resultado del paso 11 obtendremos en los marcadores el marcador modificado "("ID" = 2)"

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion con este test](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP017+Añadir+a+marcadores)
[](readme.md)