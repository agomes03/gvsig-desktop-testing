{% comment %} encoding: utf-8 {% endcomment %}

## HE00FB00C001 Ordenación en la ficha de búsqueda

### Descripción

Una vez realizada una busqueda por atributos sobre una capa, 
comprobar que podemos ordenar los resultados por un campo de la capa.


Antes de pasar el caso de prueba compruebe [aquí](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00C001&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)
 que no exista abierta una incidencia sobre él.


### Prerrequisitos

1. Haber pasado el HE00FB00C000 y que la aplicacion este justo en el 
   estado en que se quedo tras ese caso.

### Pasos

1. Ejecutar el caso de pruebas HE00FB00C000.
2. Una vez obtenidos los resultados del paso anterior, seleccionar
   la opcion "Ordenar por..." en el menu de la ventana.
3. En el cuadro dialogo seleccionar el campo "ABREV" para que ordene 
   por el (seleccionarlo y pulsar la flecha para pasarlo a la lista de
   la derecha). Pulsar "Aceptar".

### Resultado esperado

La tabla resultado de la busqueda debe mostrar los datos ordenados
alfabeticamente por la columna "ABREV".

### Reportar fallo

En caso de que los resultados obtenidos no sean los correctos puede reportar
una incidencia en el *redmine* de *gvSIG deskop* que localizará en 
https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues .

[Comprobar si hay abierta una incidencia sobre este caso de prueba](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00C001&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

[Abrir una indicendia sobre este caso de prueba](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00C001+Ordenación+en+la+ficha+de+búsqueda)


