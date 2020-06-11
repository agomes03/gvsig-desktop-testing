## HE00FB00CP022 Limpiar los parametros de busqueda

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP022&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargamos el fichero de datos, seleccionamos un valor dentro del campo de tipo integer y limpiamos la busqueda de forma correcta El resultado final es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. Añadiremos la capa *.csv* y abriremos el fichero [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
2. Mostrar la tabla de atributos en la vista
3. Seleccionar menu *Tabla*/Busqueda por atributos
4. Seleccionaremos el campo "ID"
6. Seleccionaremos el valor "5"
7. Seleccionaremos el boton "Limpiar" 

### Resultados esperados

Como resultado se limpiara el parametro de busqueda "ID = 5"

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion a esta prueba](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP022+Limpiar+los+parametros+de+busqueda)
[](readme.md)