## HE00FB00CP020 Crear una columna nueva a partir de datos de columnas existentes 

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP020&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargamos el fichero de datos y creamos una columna nueva a partir de una columna de tipo string correctamente El resultado final no es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. A�adiremos la capa *.csv* y abriremos el fichero [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
2. Mostrar la tabla de atributos en la vista
2. Seleccionar menu *Tabla*/Busqueda por atributos
3. Abriremos las herramientas extra del panel de busqueda
4. Seleccionaremos la herramienta "Columnas calculadas"
5. Pulsaremos el icono que permite crear una nueva columna calculada
6. Crearemos una nueva columna llamada "Field"
7. Seleccionaremos el campo de tipo "String"
8. Pulsaremos en el boton "Aceptar"

### Resultados esperados

Como resultado se habra creado la columna field en la tabla de atributos

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion a esta prueba](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP020+Crear+una+columna+nueva+a+partir+de+datos+de+columnas+existentes)
[](readme.md)