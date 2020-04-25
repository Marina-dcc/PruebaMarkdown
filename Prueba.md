# Informe accesibilidad

En este informe lo que se quiere revisar es el grado de accesibilidad que tiene la página web www.getbem.com


## Herramienta validación accesibilidad

En mi caso he optado por utilizar **WAVE** 
Y se han encontrado los siguientes:

* 16 errores

	> De los 16 errores, 15 son imágenes que no tienen texto alternativo, pero funcionan como link, no como imágenes, por lo que no se consideraría un error.  El otro error es por lenguaje, no tiene especificado el idioma de la página.

	**Solución** Incluir texto alternativo que especifique que esa imagen es un link y por lo tanto tiene una interacción, no es solo visual. Además de incluir el idioma de la página con su código.
	
* 5 alertas
	> Las alertas que se crean son por enlaces redundantes, ya que todos los links, están dirigidos a la misma página y la falta de título en la página con un nivel H1.  

  **Solución**: Crear páginas diferentes para cada link y que se puedan consultar las secciones por separado
	
* 11 elementos estructurales
	>Estos hacen referencia a que todos los títulos están con el mismo encabezado (h2) y que hay listas desordenadas. En principio no serían muy importantes ya que los encabezados tienen el mismo valor y la lista desordenada la han usado para incluir logos de empresas colaboradoras y no tiene que tener un orden en concreto para su entendimiento.

	**Solución**: Incluir sonido descriptivo a las imágenes