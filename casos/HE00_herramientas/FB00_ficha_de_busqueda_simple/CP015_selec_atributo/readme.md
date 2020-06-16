## HE00FB00CP015 Seleccion de un atributo 

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP015&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargamos el fichero de datos y la seleccion de atributos para realizar una busqueda sobre un campo decimal. Se probara al realizar esa busqueda que se queda como primera opcion y la mas reciente. El resultado final es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. A�adiremos la capa *.csv*
2. Mostrar la tabla de atributos en la vista
3. Seleccionar menu *Tabla*/Busqueda por atributos
4. Abriremos la opcion "Select attribute"
5. Utilizamos la barra del filtro para buscar "Decimal" 
6. Pulsaremos en el icono del "filtro de seleccion"
7. Seleccionaremos el campo "Decimal" de la lista de campos
8. Pulsaremos en el boton "Aceptar"
9. Seleccionaremos el operador "Igual a" de la lista de operadores logicos
10. Pulsaremos en el boton "Buscar"
11. Volveremos a abrir la opcion "Select attribute"
 

### Resultados esperados

Como resultado del paso 8 obtendremos el campo en la seleccion de busqueda, seguidamente como resultado del paso 10 obtendremos 9 resultados con los "ID":

- 1
- 2
- 3
- 4
- 5
- 6
- 7
- 8
- 9

y como resultado final observaremos que el campo se encuentra el primero en la seleccion de atributos

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion con este test](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP015+Seleccion+de+un+atributo)
[](readme.md)