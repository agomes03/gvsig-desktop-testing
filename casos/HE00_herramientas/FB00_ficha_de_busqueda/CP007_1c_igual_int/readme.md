## HE00FB00CP007 Busqueda de un campo de tipo integer en un shapefile

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP007&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargar el fichero shapefile,**FB_datos1.csv**, y comprobar que seleccionando un valor dentro del campo de tipo integer me escoge el registro correcto. El resultado final es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos **FB_datos1.csv**
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. A�adiremos la capa shapefile y abriremos el fichero **FB_datos1.csv**
2. Mostrar la tabla de atributos de **FB_datos1.csv** en la vista
2. Seleccionar menu Tabla/Busqueda por atributos. Escoger el atributo que queramos
3. Seleccionaremos el campo "ID"
4. Seleccionaremos el operador "Igual a"
5. Seleccionaremos el valor "2"
6. Pulsaremos en el boton "Buscar"

### Resultados esperados

Como resultado de la busqueda obtendremos 1 resultado con el "ID=2"

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion a esta prueba](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP007+Busqueda+de+un+campo+de+tipo+integer+en+un+shapefile)
[](readme.md)