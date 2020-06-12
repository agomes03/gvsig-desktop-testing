## HE00FB00CP019 Mostrar una columna que no se visualiza en la ficha de busqueda 

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP019&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargamos el fichero de datos e introducimos el campo de tipo long en la ficha de busqueda para poder realizar busquedas en ese campo El resultado final es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. Añadiremos la capa *.csv* y abriremos el fichero [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
2. Mostrar la tabla de atributos en la vista
2. Seleccionar menu *Tabla*/Busqueda por atributos
3. Abriremos las herramientas extra del panel de busqueda
4. Seleccionaremos la herramienta "Seleccionar columnas a visualizar"
5. Escribiremos "Long" en el buscador
6. Pulsaremos el filtro de seleccion y Seleccionaremos el campo
7. Pasaremos el campo seleccionado a la tabla de la derecha con las flechas
8. Pulsaremos en el boton "Aceptar"

### Resultados esperados

Como resultado se visualizara el campo de tipo long en la tabla de atributos de la ficha de busqueda

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion a esta prueba](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP019+Mostrar+una+columna+de+tipo+long+que+no+se+visualiza+en+la+ficha+de+busqueda)
[](readme.md)