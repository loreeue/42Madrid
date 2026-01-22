# 42 Madrid

Este repositorio es para documentar mi progreso en los proyectos que he realizado en **42Madrid**.

![Logo 42 Madrid](42-Madrid.jpeg)

## 🚀 Proyectos

Estos son los proyectos que he completado hasta ahora:

<details>
<summary><strong>🎯 MILESTONE 00</strong></summary>

#### [Libft](https://github.com/loreeue/Libft) - 125/100

Reimplementación de funciones esenciales de la biblioteca estándar de C, construida desde cero. Incluye utilidades como `ft_memcpy`, `ft_strchr`, manejo de listas (`ft_lstadd`), entre otras.

</details>

<details>
<summary><strong>🎯 MILESTONE 01</strong></summary>

#### [Printf](https://github.com/loreeue/Printf) - 100/100

Versión personalizada de `printf`, con compatibilidad para múltiples formatos de salida y sin depender de la implementación estándar.

#### [Born2beroot]() - 100/100

Proyecto enfocado en la configuración de un sistema Linux seguro y estable.

#### [Get_Next_Line](https://github.com/loreeue/GetNextLine) - 125/100

Implementación de una función que permite leer archivos línea por línea, optimizada para el uso eficiente de memoria y adecuada para cualquier tamaño de `BUFFER_SIZE`.

</details>

<details>
<summary><strong>🎯 MILESTONE 02</strong></summary>

#### [Push_swap](https://github.com/loreeue/Push_swap) - 100/100

Desafío algorítmico basado en la ordenación de números utilizando dos pilas. Se enfoca en encontrar la estrategia más eficiente para reducir el número de movimientos.

#### [Pipex](https://github.com/loreeue/Pipex) - 100/100 - En proceso de hacer la parte bonus

Programa que replica el comportamiento de las **pipes** en la terminal. Utiliza `fork` y `exec` para la creación de procesos y la manipulación de la redirección de entrada/salida.

#### [Fract-ol](https://github.com/loreeue/Fract-ol) - 110/100 - En proceso de hacer la parte bonus

Exploración visual de fractales usando **MiniLibX**. Soporta Mandelbrot y Julia, con navegación interactiva y zoom dinámico.

</details>

<details>
<summary><strong>🎯 MILESTONE 03</strong></summary>

#### [Philosophers](https://github.com/loreeue/Philosophers) - 100/100

Simulación del problema de los filósofos comensales, un clásico de concurrencia en programación. Implementado con hilos y mutexes para gestionar la sincronización y evitar condiciones de carrera o deadlocks.

#### [Minishell](https://github.com/jpuerto-loruzqui/42Minishell) - 100/100

Recreación simplificada de un shell de Unix, que interpreta y ejecuta comandos en una línea de entrada. Soporta pipes, redirecciones, variables de entorno, manejo de señales, y ejecución de comandos built-in como cd, echo, export, entre otros.

</details>

<details>
<summary><strong>🎯 MILESTONE 04</strong></summary>

#### [Netpractice](https://github.com/loreeue/Netpractice) - 100/100

Ejercicios interactivos para comprender los fundamentos del networking, enfocados principalmente en el direccionamiento y configuración de redes IP. Se resuelven 10 niveles dentro de una interfaz web, ajustando campos como direcciones IP, máscaras de subred y gateways para lograr una red funcional.

Cada nivel simula una red con errores, y el objetivo es diagnosticar y corregir la configuración hasta que sea válida. Este repositorio contiene las configuraciones exportadas para cada uno de los niveles resueltos.

#### [CPP-00](https://github.com/loreeue/Cpps) - 80/100

Introducción a la programación orientada a objetos con C++98. Incluye conceptos como namespaces, clases, funciones miembro, static, const, y manejo básico de streams de entrada/salida.

<details>
<summary><strong>Ejercicios</strong></summary>

* **Megaphone (ex00):** Convierte la entrada a mayúsculas.
* **PhoneBook (ex01):** Agenda de contactos con límite de 8 registros.

</details>

#### [CPP-01](https://github.com/loreeue/Cpps) - 100/100

Profundización en la gestión de memoria, referencias, punteros y estructuras de control. Este módulo introduce el uso de `new/delete`, referencias, punteros a funciones miembro y la instrucción `switch`, todo dentro del estándar C++98.

<details>
<summary><strong>Ejercicios</strong></summary>

* **BraiiiiiiinnnzzzZ (ex00):** Clase `Zombie` con método `announce()`. Se practica la creación en stack vs heap.
* **Moar brainz! (ex01):** Función `zombieHorde()` que genera múltiples zombies en memoria dinámica.
* **HI THIS IS BRAIN (ex02):** Comparación de punteros y referencias con una string.
* **Unnecessary violence (ex03):** Clases `HumanA` y `HumanB` que usan un `Weapon` con referencia o puntero.
* **Sed is for losers (ex04):** Reemplazo manual de texto en archivos, sin usar `replace()`.
* **Harl 2.0 (ex05):** Clase `Harl` con niveles de log, implementado usando punteros a funciones miembro.
* **Harl filter (ex06):** Filtro de mensajes según nivel, usando `switch`.

</details>

#### [CPP-02](https://github.com/loreeue/Cpps) - 100/100

Introducción al **polimorfismo ad-hoc**, **sobrecarga de operadores** y la **forma canónica ortodoxa** de clases en C++98. Este módulo profundiza en la construcción de clases robustas y reutilizables, aplicando buenas prácticas de diseño orientado a objetos. Se implementa una clase de números en punto fijo con operadores personalizados y lógica geométrica.

<details>
<summary><strong>Ejercicios</strong></summary>

* **My First Class in Orthodox Canonical Form (ex00):** Clase `Fixed` en forma canónica, con acceso a valores internos.
* **Towards a more useful fixed-point number class (ex01):** Conversión entre `int`, `float` y sobrecarga del operador `<<`.
* **Now we’re talking (ex02):** Sobrecarga de operadores aritméticos, de comparación e incremento. Métodos estáticos `min` y `max`.
* **BSP (ex03):** Clase `Point` y función `bsp()` para determinar si un punto está dentro de un triángulo usando coordenadas baricéntricas.

</details>

#### [CPP-03](https://github.com/loreeue/Cpps) - 100/100

Este módulo se centra en la **herencia en C++98**, aplicando los principios de programación orientada a objetos. A través de clases derivadas y herencia múltiple, se exploran conceptos como el encadenamiento de constructores, el uso de `virtual` implícito, ocultamiento de nombres y ambigüedad en la herencia.

<details>
<summary><strong>Ejercicios</strong></summary>

* **Aaaaand... OPEN! (ex00):** Clase `ClapTrap` con atributos de estado (`hitPoints`, `energyPoints`, `attackDamage`) y métodos básicos (`attack`, `takeDamage`, `beRepaired`). Se imprime información detallada en cada acción y constructor/destructor.
* **Serena, my love! (ex01):** Clase `ScavTrap`, derivada de `ClapTrap`. Modifica atributos por defecto y añade el método especial `guardGate()`. Se refuerza el concepto de herencia simple.
* **Repetitive work (ex02):** Clase `FragTrap`, otra derivada de `ClapTrap`, con valores únicos y el método especial `highFivesGuys()`. Se enfatiza el constructor/destructor chaining.
* **Now it’s weird! (ex03):** Clase `DiamondTrap`, que **hereda de `ScavTrap` y `FragTrap`**. Usa herencia múltiple y atributos combinados. Implementa el método `whoAmI()` que muestra tanto su nombre como el de su base `ClapTrap`. Maneja ambigüedad de herencia y sobrescritura.

</details>

#### [CPP-04](https://github.com/loreeue/Cpps) - 100/100

Este módulo profundiza en el **polimorfismo por subtipado**, el uso de **clases abstractas**, y la simulación de **interfaces en C++98**. Se implementan jerarquías de clases con funciones virtuales puras, uso correcto de `new`/`delete`, y copias profundas para evitar errores de memoria.

<details>
<summary><strong>Ejercicios</strong></summary>

* **Polimorfismo básico (ex00):** Clases `Animal`, `Dog`, `Cat` con `makeSound()` virtual. Se demuestra el polimorfismo mediante punteros a clase base. También se implementa `WrongAnimal` y `WrongCat` para ilustrar el error al omitir `virtual`.

* **Brainstorming (ex01):** Introducción de la clase `Brain`, que contiene 100 ideas. `Dog` y `Cat` manejan su propio `Brain*`. Se implementan destructores adecuados y **copias profundas** para evitar compartir memoria entre instancias.

* **Clase abstracta (ex02):** `Animal` se convierte en clase abstracta al incluir `makeSound() = 0`. Se impide instanciación directa y se mantiene la funcionalidad previa mediante clases derivadas.

* **Interfaces y recapitulación (ex03):** Sistema tipo RPG con materias mágicas (`AMateria`, `Ice`, `Cure`). Se implementan las interfaces `ICharacter` y `IMateriaSource`, y sus clases concretas `Character` y `MateriaSource`. Se prueba el uso de `clone()`, `equip()`, `use()` y la gestión correcta de memoria y copias profundas.

</details>

#### [Cub3D](https://github.com/jpuerto-loruzqui/Cub3D) - 110/125

Mi primer motor de **ray casting** con **MiniLibX**, inspirado en *Wolfenstein 3D*. Permite recorrer un laberinto en primera persona con paredes texturizadas y control de la cámara en tiempo real.

Características principales:
* Renderizado 3D con texturas según orientación (N/S/E/O).
* Colores configurables para suelo y techo.
* Controles fluidos con `W/A/S/D` y flechas izquierda/derecha.
* Parsing robusto del archivo `.cub` para mapas y configuraciones.

Bonus implementados:
* ✅ Colisiones con paredes.
* ✅ Minimap en tiempo real.

</details>

<details>
<summary><strong>🎯 MILESTONE 05</strong></summary>

#### [Inception](https://github.com/loreeue/Inception) - 100/100

Proyecto dedicado a la **containerización con Docker**. Se construye una infraestructura completa formada por **Nginx**, **WordPress** y **MariaDB**, cada uno en su propio contenedor, gestionados mediante **Docker Compose**.
Incluye volúmenes para persistencia, redes internas, y scripts personalizados para inicializar y configurar cada servicio.

Perfecto 👍
Solo tienes que **añadir ft_irc en el milestone correcto (05)** manteniendo el mismo estilo que el resto del README. Te dejo el **bloque exacto listo para copiar y pegar**, ya redactado y coherente con lo que ya tienes.


#### [IRC](https://github.com/ft-IRClive/ft_irc) - 96/100

Implementación de un **servidor IRC** en **C++98**, siguiendo el protocolo definido en la **RFC 1459**. El servidor permite la conexión simultánea de múltiples clientes reales (como **HexChat** o `nc`) y la gestión completa de usuarios y canales.

Características principales:

* Servidor concurrente usando **sockets TCP**.
* Multiplexación de I/O mediante **poll()**.
* Autenticación completa (`PASS`, `NICK`, `USER`).
* Gestión de canales y operadores.
* Implementación de comandos IRC:

  * `JOIN`, `PART`, `TOPIC`
  * `MODE`, `INVITE`, `KICK`
  * `PRIVMSG`, `WHO`, `QUIT`
* Manejo correcto de desconexiones y errores estándar IRC.


#### [CPP-05](https://github.com/loreeue/Cpps) - 100/100

Este módulo se centra en el uso avanzado de **excepciones**, el diseño correcto de **jerarquías de clases**, y la aplicación práctica de **herencia, clases abstractas y polimorfismo** en C++98. Se introduce además el uso de **patrones de diseño simples**, como el **Factory**, y se refuerza la importancia del diseño orientado a responsabilidades.

<details>
<summary><strong>Ejercicios</strong></summary>

* **Mommy, when I grow up, I want to be a bureaucrat! (ex00):**
  Implementación de la clase `Bureaucrat`, con validación estricta de rangos y uso de excepciones (`GradeTooHighException`, `GradeTooLowException`). Se refuerza el concepto de invariantes de clase y el manejo de errores mediante `try/catch`.

* **Form up, maggots! (ex01):**
  Introducción de la clase `Form`, que interactúa con `Bureaucrat`. Se trabajan relaciones entre clases, control de permisos mediante grados, y propagación de excepciones. Se refuerza el principio de responsabilidad única.

* **No, you need form 28B, not 28C... (ex02):**
  `Form` se convierte en una **clase abstracta (`AForm`)**. Se implementan formularios concretos (`ShrubberyCreationForm`, `RobotomyRequestForm`, `PresidentialPardonForm`) que sobrescriben métodos virtuales. Se demuestra el **polimorfismo dinámico** y el uso correcto de destructores virtuales.

* **At least this beats coffee-making (ex03):**
  Implementación de la clase `Intern`, que actúa como una **fábrica de formularios**. Se aplica un patrón **Factory** para desacoplar la creación de objetos del código cliente, devolviendo punteros a `AForm` sin exponer las clases concretas.

</details>

#### [CPP-06](https://github.com/loreeue/Cpps) - 100/100

Este módulo introduce el uso correcto de los **casts en C++98**, la conversión explícita de tipos y el **RTTI (Run-Time Type Identification)**. Se trabaja la diferencia entre conversiones seguras en tiempo de compilación y comprobaciones dinámicas en tiempo de ejecución.

<details>
<summary><strong>Ejercicios</strong></summary>

* **Conversion of scalar types (ex00):**
  Implementación de la clase `ScalarConverter`, no instanciable, con un método estático que detecta el tipo real de un literal (`char`, `int`, `float`, `double`) y lo convierte explícitamente a los demás tipos. Maneja pseudo-literales (`nan`, `inf`, etc.) y conversiones imposibles.

* **Serialization (ex01):**
  Clase `Serializer` que convierte un puntero a `uintptr_t` y viceversa. Se utiliza `reinterpret_cast` para demostrar la conversión entre direcciones de memoria y tipos enteros sin pérdida de información.

* **Identify real type (ex02):**
  Jerarquía simple (`Base`, `A`, `B`, `C`) para identificar el tipo real de un objeto usando `dynamic_cast`. Se compara el comportamiento del cast con punteros y con referencias, sin usar `typeid`.

</details>

#### [CPP-07](https://github.com/loreeue/Cpps) - 90/100

Este módulo introduce el uso de **templates en C++98**, permitiendo escribir código genérico y reutilizable sin sacrificar seguridad de tipos. Se trabajan **funciones template**, **templates de clases**, y la correcta gestión de memoria y excepciones en estructuras genéricas, respetando la forma canónica ortodoxa.

<details>
<summary><strong>Ejercicios</strong></summary>

* **Start with a few functions (ex00):**
  Implementación de **funciones template** (`swap`, `min`, `max`) válidas para cualquier tipo que soporte operadores de comparación. Se refuerza el concepto de definición de templates en headers y la resolución en tiempo de compilación.

* **Iter (ex01):**
  Función template `iter` que aplica una función a cada elemento de un array. Se trabaja el soporte tanto para **arrays const como no const**, y el paso de funciones como parámetros genéricos.

* **Array (ex02):**
  Implementación de una **clase template `Array<T>`**, con gestión dinámica de memoria usando `new[]`, copia profunda, operador `[]` con control de límites mediante excepciones, y método `size()`. Se refuerza el diseño seguro de contenedores genéricos sin usar STL.

</details>

#### [CPP-08](https://github.com/loreeue/Cpps) - 100/100

Este módulo introduce el uso real de la **STL (Standard Template Library)** en C++98. Se trabajan **contenedores**, **iteradores** y **algoritmos genéricos**, entendiendo cómo se combinan para escribir código reutilizable, eficiente y bien abstraído.

<details>
<summary><strong>Ejercicios</strong></summary>

* **Easy find (ex00):**
  Implementación de la función template `easyfind`, que busca un `int` dentro de un contenedor STL genérico usando obligatoriamente algoritmos STL (`std::find`). Refuerza el uso de **iteradores** y algoritmos independientes del contenedor.

* **Span (ex01):**
  Clase `Span` que almacena hasta `N` enteros y calcula la menor (`shortestSpan`) y mayor (`longestSpan`) diferencia entre ellos. Uso de algoritmos STL como `std::sort`, `std::min_element` y `std::max_element`. Se implementa `addRange` para añadir múltiples valores usando rangos de iteradores.

* **MutantStack (ex02):**
  Clase template que hereda de `std::stack` y mantiene su comportamiento LIFO, añadiendo la posibilidad de iterar sobre sus elementos. Expone los iteradores del contenedor interno y permite recorrer la pila como un contenedor STL estándar, comparando su comportamiento con `std::list`.

</details>

#### [CPP-09](https://github.com/loreeue/Cpps) - 100/100

Este módulo consolida el uso avanzado de la **STL en C++98**, combinando **contenedores**, **algoritmos**, **iteradores** y **medición de rendimiento**. Se hace especial hincapié en la correcta elección de estructuras de datos, la validación de entradas y el diseño eficiente de algoritmos.

<details>
<summary><strong>Ejercicios</strong></summary>

* **Bitcoin Exchange (ex00):**
  Programa que calcula el valor de una cantidad de bitcoin en una fecha determinada usando una base de datos CSV.
  Se trabaja con **mapas ordenados**, parsing robusto de fechas, validación de entradas (`float`, rangos válidos), y búsqueda de la **fecha más cercana inferior** cuando no existe coincidencia exacta.
  Se refuerza el manejo de errores y el uso correcto de contenedores asociativos.

* **Reverse Polish Notation (ex01):**
  Evaluador de expresiones matemáticas en **notación polaca inversa (RPN)**.
  Uso de un contenedor tipo **stack** para procesar operandos y operadores (`+ - * /`), validación estricta de la expresión y gestión de errores en tiempo de ejecución.
  No se permiten paréntesis ni números decimales.

* **PmergeMe (ex02):**
  Implementación del algoritmo **Ford-Johnson (merge-insert sort)** para ordenar secuencias de enteros positivos.
  Se utilizan **dos contenedores distintos** para comparar rendimiento, mostrando el tiempo de ejecución de cada uno con precisión suficiente para apreciar diferencias.
  El programa gestiona secuencias de al menos **3000 elementos**, mide tiempos y muestra el antes/después del ordenado.

</details>

</details>

<details>
<summary><strong>🎯 MILESTONE 06</strong></summary>


</details>
