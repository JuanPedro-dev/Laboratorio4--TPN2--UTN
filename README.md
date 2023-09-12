<h1 style="text-align:center">  💻 Laboratorio 4 - TP Nº 2💻  </h1>

Tecnicatura Universitaria en Programación (UTN): vemos las herramientas, tecnologías y lenguajes básicos en el desarrollo web. 
<br> 
Este trabajo práctico esta enfocado en creación de Objetos, Clases y bases de javascript. 
Algunos Ejercicio puede que tengan más de un proyecto a modo de ejercitar manejo del DOM, diseño u otros conceptos. 

⚠️ ***Ignore completamente este proyecto.*** ⚠️

<h2 style="text-align:center">📋 TP Nº 2 - Objetos y Clases 📋 </h2>

#### 1- Crear un objeto y mostrar propiedades
Crea un objeto que represente a una persona con propiedades como nombre, edad y profesión. Luego, muestra estas propiedades utilizando alert.

#### 2- Clase de Libro
Crea una clase llamada "Libro" que tenga propiedades como título, autor y año de publicación. 
Crea un método que muestre la información del libro en un formato legible y utiliza prompts para obtener la información del usuario. Luego, crea una instancia de la clase y muestra la información utilizando alert.

#### 3- Crear una Clase y sus Métodos
Utiliza la clase generada en el punto 1 añadiendo los siguientes métodos:
* constructor(nombre, edad, profesión): Inicializa el nombre, la edad de la persona y su profesión. <br>
* saludar(): Muestra un saludo en un alert que incluya el nombre y la edad de la persona.<br>

Luego, crea una instancia de la clase Persona utilizando los datos proporcionados por el usuario a través de prompts y muestra el saludo utilizando el método saludar().

#### 4- Herencia con Superhéroes
Crea una clase base llamada Superheroe con los siguientes métodos: 
* constructor(nombre, poder): Inicializa el nombre y el poder del superhéroe. 
* presentarse(): Muestra un alert con el nombre del superhéroe y su poder. 

Crea una clase que herede de Superheroe llamada Villano con un método adicional: 
* constructor(nombre, poder, plan): Inicializa el nombre, poder y plan del villano. 
* amenazar(): Muestra un alert con el plan del villano. 

Crea instancias de ambas clases utilizando datos ingresados por el usuario a través de prompts y muestra sus presentaciones y amenazas respectivas.

#### 5- Gestión de Libros
Utiliza la clase generada en el punto 1 añadiendo los siguientes métodos:

* constructor(titulo, autor, año de publicación): Inicializa el título, el autor del libro y el año en se lanzó el libro.
* mostrarDetalles(): Muestra un alert con los detalles del libro.

Crea una clase que herede de Libro llamada LibroDigital con un método adicional:
* constructor(titulo, autor, año de publicación, formato): Inicializa el título, autor, año en que lanzó y formato del libro digital.
* mostrarFormato(): Muestra un alert con el formato del libro digital.

Permite al usuario ingresar información sobre un libro físico y un libro digital a través de prompts y muestra sus detalles y formatos respectivos utilizando los métodos correspondientes.

#### 6- Map para nombres en mayúsculas
Crea un array de nombres y utiliza el método map para convertir todos los nombres a mayúsculas. Luego, muestra los nombres en mayúsculas utilizando alert.

#### 7- Encontrar un número en un array
Crea un array de números y utiliza el método find para buscar un número específico ingresado por el usuario utilizando un prompt. Si el número se encuentra, muestra un mensaje utilizando alert.

#### 8- Filtrar números pares
Crea un array de números y utiliza el método filter para obtener un nuevo array que contenga solo los números pares. Muestra los números pares utilizando alert.