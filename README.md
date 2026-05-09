- Tarea Individual:  Sistema de Vehiculos
- Enunciado: Diseña e implementa un sistema de vehiculos en Java 

Este ejercicio implementa un sistema de vehiculos utilizando interfaces y herencias en Java.
Se creo una clase vehiculo el cual va a contener los atributos y metodos comunes que tiene un vehiculo.
Se utilizaron las subclases Auto,Moto y Camion que heredan los atributos y metodos de la clase padre Vehiculo el cual se sobreescribe
el metodo describir() utilizando @Override.

Se utilizo la interfaz Electrico el cual se implemento por la clase Auto para agregar comportamiento relacionado con 
con bateria y autonomia

Por ultimo se utilizo el main polimorfismo mediante un arreglo Vehiculo[] para recorrer objetos de diferentes
subclases de manera uniforme utilizando el bucle for

- Tarea 1: Sistema de Figuras Geometricas
- Enunciado: Diseña e implementa un sistema de figuras geometricas en Java utilizando una clase
abstracta como base
Este ejercicio implementa un sistema de Figuras Geometricas utilizando clases abstractas y herencias.
Se creo una clase abstracta llamada Figura el cual contiene atributos comunes y metodos abstractos que son
calcularArea() y calcularPerimetro()

Las subclases Circulo,Rectangulo y TrianguloRectangulo van a heredar los atributos de Figura e implementan sus propios
calculos utilizando @Override.

El metodo describir() se definio en la clase padre para poder reutilizar codigo en todas las clases hijas.

Por ultimo en el main se utilizo el polimorfismo con un arreglo Figura[] para trabajar con las distintas figuras
de forma uniforme con el bucle for

- Tarea 2: Sistema de Empleados con Jerarquia
- Enunciado: Diseña un sistema de gestion de empleados para una empresa con distintos tipos de
contrato. Deberas modelar la jerarquia con una clase abstracta y subclases especializadas.

Este ejercicio implementa un sistema de Empleados utilizando lo anterior visto clases abstractas, interfaces y herencia en Java.
La clase padre Empleado va a ser abstracta ya que va a definir los atributos y comportamientos comunes
de todos los empleados, incluyendo el metodo abstracto definida que es calcularSalario()

Las subclases o clases hijas EmpleadoPorHora,EmpleadoFijo y EmpleadoComision van a sobreescribir el metodo
calcularSalario() usando @Override y implementando cad uno sus propiso calculos

La interfaz Bonificable lo utilizamos para el EmpleadoFijo y EmpleadoComision para poder calcular los bonos adicionales.

Por ultimo en el main se utilizo nuevamente el polimorfismo con otro arreglo llamado Empleado y tambien 
se siguio la instruccion de utilizar instanceof para poder identificar los objetos que se va a implementar en 
Bonificable

