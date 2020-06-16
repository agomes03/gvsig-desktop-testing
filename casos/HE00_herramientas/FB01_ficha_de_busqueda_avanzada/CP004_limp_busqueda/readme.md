## HE00FB01CP004 Limpiar las expresiones de la busqueda avanzada

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB01CP004&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargamos el fichero de datos, seleccionamos la expresion "ID = 3" y limpiamos la busqueda de forma correcta. El resultado final es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. Añadiremos la capa *.csv*
2. Mostrar la tabla de atributos en la vista
3. Seleccionar menu *Tabla*/Busqueda por atributos
4. Seleccionaremos la pestaña de "Busqueda avanzada"
5. Pulsaremos en el icono del "Constructor de expresiones"
6. Introduciremos la expresion "ID = 3" 
7. Pulsaremos en el boton "Aceptar"
7. Seleccionaremos el boton "Limpiar" 

### Resultados esperados

Como resultado se limpiara la expresion de busqueda "ID = 3".

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion con este test](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB01CP004+Limpiar+las+expresiones+de+la+busqueda+avanzada)
[](readme.md)