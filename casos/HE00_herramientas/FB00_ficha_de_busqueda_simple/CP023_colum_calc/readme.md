## HE00FB00CP023 Crear una columna calculada nueva a partir de datos de columnas existentes 

[Primero compruebo si hay una peticion abierta](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP023&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargamos el fichero de datos y creamos una columna calculada nueva a partir de un campo string y uno long de forma correcta. El resultado final es correcto.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos [FB_datos1.csv](https://github.com/agomes03/gvsig-desktop-testing/blob/master/data/HE00FB00/FB00_datos1.csv)
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. Aņadiremos la capa *.csv*
2. Mostrar la tabla de atributos en la vista
3. Seleccionar menu *Tabla*/Busqueda por atributos
4. Abriremos las herramientas extra del panel de busqueda
5. Seleccionaremos la herramienta "Columnas calculadas"
6. Pulsaremos el icono que permite crear una nueva columna calculada
7. Crearemos una nueva columna llamada "Field"
8. Rellenamos los campos de esa columna
9. Pulsaremos el icono de "Constructor de expresiones"
10. Creamos la expresion "String + Long" que rellene la columna
11. Pulsaremos el boton "Aplicar cambios"
12. Pulsaremos en el boton "Aceptar"

### Resultados esperados

Como resultado se habra creado la columna llamada field en la tabla de atributos rellena con el resultado de la expresion que hemos creado. Como resultado de la busqueda obtendremos 9 elementos:

- yo11000
- yo22000
- yo33000
- yo44000
- yo55000
- yo66000
- yo77000
- yo88000
- yo99000

### Reportar fallo

En caso de que resultados sean incorrectos, puedes informar del problema en redmine de gvSIG desktop. Puedes encontrarlo en: https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues 

[Abro una nueva publicacion con este test](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP023+Crear+una+columna+calculada++nueva+a+partir+de+datos+de+columnas+existentes)
[](readme.md)