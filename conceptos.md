En programación y computación, un stack (o pila en español) es una estructura de datos que sigue el principio de "último en entrar, primero en salir" (LIFO, por sus siglas en inglés: Last In, First Out). Esto significa que el último elemento que se agrega al stack es el primero en ser eliminado.

Características principales de un stack:
Operaciones básicas:

Push: Agrega un elemento al top (parte superior) de la pila.
Pop: Elimina el elemento en la parte superior de la pila.
Peek o Top: Muestra el elemento en la parte superior de la pila sin eliminarlo.
IsEmpty: Verifica si la pila está vacía.
Estructura LIFO: En un stack, los elementos se apilan unos sobre otros, y sólo se puede acceder al último elemento añadido. Es como una pila de platos donde solo puedes tomar o agregar el plato superior.
3 Usos comunes:

Control de flujo de ejecución: En muchos lenguajes de programación, se utiliza un stack para manejar el control de funciones y llamadas. Cada vez que se llama a una función, se apilan datos de esa función (como las variables locales) y, cuando la función termina, se eliminan.
Deshacer/rehacer: Los stacks son útiles en aplicaciones que permiten deshacer o rehacer acciones, como en editores de texto.
Evaluación de expresiones: Los stacks se usan para evaluar expresiones matemáticas o manejar paréntesis en notación infija, prefija y postfija.
Ejemplo visual:
Imagina una pila de libros. Si apilas tres libros (A, B y C), el libro C estará en la parte superior. Si quitas un libro, será el C, porque es el último en ser apilado.

Ejemplo de un stack en pseudocódigo:
Pila = []  // Crear una pila vacía
Push(Pila, 10)  // Apilar el número 10
Push(Pila, 20)  // Apilar el número 20
Pop(Pila)  // Eliminar el 20 (último en entrar)
Top(Pila)  // Mostrar 10, ya que es el único que queda

Frontend se refiere a las tecnologías utilizadas en el desarrollo web del lado del cliente, es decir, aquellas que se ejecutan en el navegador del usuario. Las tres tecnologías principales del frontend son HTML, CSS y JavaScript.

HTML: Es un lenguaje de marcado que define la estructura de los contenidos de una página web, como encabezados, párrafos y tablas. Es el "esqueleto" de la página.
CSS: Es un lenguaje de hojas de estilo que se utiliza para definir la apariencia visual de la página, como colores, tamaños, tipos de letra y espaciado.
JavaScript: Es un lenguaje de programación que permite la interactividad y el comportamiento dinámico de la página web, como respuestas a las acciones del usuario.
Aunque existen otros lenguajes y herramientas como ActionScript, Java, o Silverlight, HTML, CSS y JavaScript son los más comunes. Además, hay frameworks, librerías y preprocesadores que facilitan el desarrollo frontend, pero todos giran en torno a estas tres tecnologías principales.

El objetivo del frontend es ofrecer una experiencia de usuario fluida, con buen diseño y facilidad de uso.

El Backend se refiere a las tecnologías que funcionan del lado del servidor y son responsables de interactuar con bases de datos, manejar sesiones de usuario, gestionar la lógica del servidor y servir las vistas que el desarrollador frontend crea. Las tecnologías backend son más diversas y pueden incluir lenguajes como PHP, Python, Java, .NET, entre otros, y bases de datos como SQL, MongoDB y MySQL.

El objetivo del backend es procesar los datos recibidos desde el frontend (la parte visible para el usuario), realizando tareas como verificar credenciales o buscar información en la base de datos. Esta separación entre frontend y backend permite que el frontend se enfoque en la interfaz de usuario y la experiencia, mientras que el backend se encarga del procesamiento y la lógica.

El backend y frontend son independientes pero se comunican entre sí. Por ejemplo, cuando un usuario inicia sesión, sus datos son enviados al backend, que valida la información con la base de datos y luego envía una respuesta al frontend.

En el mundo del backend, existen más lenguajes que en el frontend, y los desarrolladores backend no necesitan conocer todos. También se ha popularizado el uso de JavaScript en el backend gracias a Node.js, que permite ejecutar JavaScript en el servidor.

Además de los lenguajes de programación, las herramientas del backend incluyen editores de código, compiladores, depuradores, gestores de bases de datos y otras tecnologías relacionadas con la seguridad y el rendimiento
