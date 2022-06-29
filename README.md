# Patrones
Builder:
	Gracias a builder podemos crear objetos siguiendo diferentes pasos dependiendo del como queremos que sea nuestro
	objeto. La computadora fisicamente tiene diferentes componentes los cuales pueden ser agregados según el modelo
	que se desee construir, por ejemplo una laptop puede tener memoria ssd o memoria hdd marcando así diferentes caminos
	para llegar al resultado final.

Singleton: 
	Singleton nos permite manejar una sola instancia de un objeto, para este caso podriamos tener una sola instancia 
	de cada modelo de laptop que se maneja para la distribución de esta forma la compañia puede tener el modelo intacto
	y no arriesgarse a que este sea cambiado, para cumplir cumplir cada modelo se debería tratar como un objeto 
	independiente.

Factory method:
	Gracias a este partron de diseño podriamos manejar un clase padre computadora de las cuales van a heredar como 
	objetos hijos cada uno de los modelos que maneja la compañia en este caso el ROG y el Zenbook e implementando
	los creadores concretos cada uno se encargaria de crear el modelo solicitado. Un punto negativo de usar este patron
	es que al ser una empresa dedicada al ensamblaje podria afectar a temas de escalabilidad en caso de que quiera 
	manejar diferentes productos.

Abstract factory:
	Abstract factory permite desarrollar diferentes productos con sus variantes respectivas (modelos de las computadoras)
	y de acuerdo a las necesidades del cliente el sistema se encargaría de seleccionar la fabrica y el modelo necesario 
	para cumplir con la solicitud. 