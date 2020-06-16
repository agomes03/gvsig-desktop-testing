{% comment %} encoding: utf-8 {% endcomment %}

## HE00FB00C000 Búsqueda simple en un shape.

### Descripción

Cargar un shape, **ne_110m_admin_0_countries**, y comprobar que se puede realizar una
busqueda sobre una de sus columnas utilizando la *ficha de busqueda*. 

Antes de pasar el caso de prueba compruebe [aquí](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00C000&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)
 que no exista abierta una incidencia sobre él.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1+* con el proveedor de shape cargado.
2. Tener acceso al shape **shape/ne_110m_admin_0_countries.shp**.
3. Tener arrancada la aplicacion con una vista nueva y vacia activa.

### Pasos

1. Cargar la capa **shape/ne_110m_admin_0_countries.shp** en la vista.
2. Seleccionar menu **layer/Busqueda por attributos**. Al hacerlo
   aparecera la ficha de busqueda con 177 elementos.
3. Seleccionaremos el campo "CONTINENT"
4. Seleccionaremos el operador "Igual a"
5. Seleccionaremos el valor "Oceania"
6. Pulsaremos en el boton "Buscar"

### Resultado esperado

Como resultado de la busuqeda obtendremos 7 elementos:
- Fiji
- P.N.G
- Van.
- New C.
- S. Is.
- N.Z.
- Auz.

### Reportar fallo

En caso de que los resultados obtenidos no sean los correctos puede reportar
una incidencia en el *redmine* de *gvSIG deskop* que localizará en 
https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues .

[Comprobar si hay abierta una incidencia sobre este caso de prueba](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00C000&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

[Abrir una indicendia sobre este caso de prueba](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00C000+Busqueda+simple+en+un+shape)



