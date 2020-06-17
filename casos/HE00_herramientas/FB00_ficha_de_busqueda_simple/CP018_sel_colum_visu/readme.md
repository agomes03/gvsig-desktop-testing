## HE00FB00CP018 Mostrar una columna que no se visualiza en la ficha de busqueda 

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP018&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargamos el fichero de datos e introducimos el campo long en la ficha de busqueda para poder realizar busquedas en ese campo de forma correcta. El resultado final es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. Añadiremos la capa *.csv*
2. Mostrar la tabla de atributos en la vista
3. Seleccionar menu *Tabla*/Busqueda por atributos
4. Abriremos las herramientas extra del panel de busqueda
5. Seleccionaremos la herramienta "Seleccionar columnas a visualizar"
6. Escribiremos "Long" en el buscador
7. Pulsaremos en el icono del filtro de seleccion 
8. Seleccionaremos el campo
9. Pasaremos el campo seleccionado a la tabla de la derecha con las flechas
10. Pulsaremos en el boton "Aceptar"

### Resultados esperados

Como resultado se visualizara el campo de tipo long en la tabla de atributos de la ficha de busqueda que antes no se mostraba.

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion con este test](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP018+Mostrar+una+columna+que+no+se+visualiza+en+la+ficha+de+busqueda)
[](readme.md)