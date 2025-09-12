# 00002024_practica2_seccion1

Analicemos ¿Porqué cambia el posicionamiento de las cajas internas al div principal?, ¿Qué pasa si me solicitan hacer
un cambio en el orden de los elementos pero sin tocar los archivos html y js, será que puedo lograrlo a traves de
CSS?.

el posicionamiento cambia ya que se le asigna un flex determinado, por lo que cambia el diseño predeterminado. Si se puede lograr cambiar el orden de los elementos con la propiedad order.

Analicemos ¿Qué hacen estás propiedades?
with de .box div da un valor especifico a cada div dentro del div .box, y cuando se especifica la regla a first-child, este se sobreescribe y especifica al primer div un tamaño diferente.