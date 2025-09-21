# 42 Madrid

Este repositorio es para documentar mi progreso en los proyectos que he realizado en **42Madrid**.

![Logo 42 Madrid](42-Madrid.jpeg)

## 🚀 Proyectos

Estos son los proyectos que he completado hasta ahora:

### 🎯 MILESTONE 00
#### [Libft](https://github.com/loreeue/Libft) - 125/100

Reimplementación de funciones esenciales de la biblioteca estándar de C, construida desde cero. Incluye utilidades como `ft_memcpy`, `ft_strchr`, manejo de listas (`ft_lstadd`), entre otras.

---

### 🎯 MILESTONE 01
#### [Printf](https://github.com/loreeue/Printf) - 100/100

Versión personalizada de `printf`, con compatibilidad para múltiples formatos de salida y sin depender de la implementación estándar.

#### [Born2beroot]() - 100/100

Proyecto enfocado en la configuración de un sistema Linux seguro y estable.

#### [Get_Next_Line](https://github.com/loreeue/GetNextLine) - 125/100

Implementación de una función que permite leer archivos línea por línea, optimizada para el uso eficiente de memoria y adecuada para cualquier tamaño de `BUFFER_SIZE`.

---

### 🎯 MILESTONE 02
#### [Push_swap](https://github.com/loreeue/Push_swap) - 100/100

Desafío algorítmico basado en la ordenación de números utilizando dos pilas. Se enfoca en encontrar la estrategia más eficiente para reducir el número de movimientos.

#### [Pipex](https://github.com/loreeue/Pipex) - 100/100 - En proceso de hacer la parte bonus

Programa que replica el comportamiento de las **pipes** en la terminal. Utiliza `fork` y `exec` para la creación de procesos y la manipulación de la redirección de entrada/salida.

#### [Fract-ol](https://github.com/loreeue/Fract-ol) - 110/100 - En proceso de hacer la parte bonus

Exploración visual de fractales usando **MiniLibX**. Soporta Mandelbrot y Julia, con navegación interactiva y zoom dinámico.

---

### 🎯 MILESTONE 03
#### [Philosophers](https://github.com/loreeue/Philosophers) - 100/100

Simulación del problema de los filósofos comensales, un clásico de concurrencia en programación. Implementado con hilos y mutexes para gestionar la sincronización y evitar condiciones de carrera o deadlocks.

#### [Minishell](https://github.com/jpuerto-loruzqui/42Minishell) - 100/100

Recreación simplificada de un shell de Unix, que interpreta y ejecuta comandos en una línea de entrada. Soporta pipes, redirecciones, variables de entorno, manejo de señales, y ejecución de comandos built-in como cd, echo, export, entre otros.

### 🎯 MILESTONE 04
#### [Netpractice](https://github.com/loreeue/Netpractice) - 100/100

Ejercicios interactivos para comprender los fundamentos del networking, enfocados principalmente en el direccionamiento y configuración de redes IP. Se resuelven 10 niveles dentro de una interfaz web, ajustando campos como direcciones IP, máscaras de subred y gateways para lograr una red funcional.

Cada nivel simula una red con errores, y el objetivo es diagnosticar y corregir la configuración hasta que sea válida. Este repositorio contiene las configuraciones exportadas para cada uno de los niveles resueltos.

#### [CPP-00](https://github.com/loreeue/Cpps) - 80/100

Introducción a la programación orientada a objetos con C++98. Incluye conceptos como namespaces, clases, funciones miembro, static, const, y manejo básico de streams de entrada/salida.

Ejercicios:

* **Megaphone (ex00):** Convierte la entrada a mayúsculas.
* **PhoneBook (ex01):** Agenda de contactos con límite de 8 registros.

#### [CPP-01](https://github.com/loreeue/Cpps) - 100/100

Profundización en la gestión de memoria, referencias, punteros y estructuras de control. Este módulo introduce el uso de `new/delete`, referencias, punteros a funciones miembro y la instrucción `switch`, todo dentro del estándar C++98.

Ejercicios:

* **BraiiiiiiinnnzzzZ (ex00):** Clase `Zombie` con método `announce()`. Se practica la creación en stack vs heap.
* **Moar brainz! (ex01):** Función `zombieHorde()` que genera múltiples zombies en memoria dinámica.
* **HI THIS IS BRAIN (ex02):** Comparación de punteros y referencias con una string.
* **Unnecessary violence (ex03):** Clases `HumanA` y `HumanB` que usan un `Weapon` con referencia o puntero.
* **Sed is for losers (ex04):** Reemplazo manual de texto en archivos, sin usar `replace()`.
* **Harl 2.0 (ex05):** Clase `Harl` con niveles de log, implementado usando punteros a funciones miembro.
* **Harl filter (ex06):** Filtro de mensajes según nivel, usando `switch`.

#### [CPP-02](https://github.com/loreeue/Cpps) - 100/100

Introducción al **polimorfismo ad-hoc**, **sobrecarga de operadores** y la **forma canónica ortodoxa** de clases en C++98. Este módulo profundiza en la construcción de clases robustas y reutilizables, aplicando buenas prácticas de diseño orientado a objetos. Se implementa una clase de números en punto fijo con operadores personalizados y lógica geométrica.

Ejercicios:

* **My First Class in Orthodox Canonical Form (ex00):** Clase `Fixed` en forma canónica, con acceso a valores internos.
* **Towards a more useful fixed-point number class (ex01):** Conversión entre `int`, `float` y sobrecarga del operador `<<`.
* **Now we’re talking (ex02):** Sobrecarga de operadores aritméticos, de comparación e incremento. Métodos estáticos `min` y `max`.
* **BSP (ex03):** Clase `Point` y función `bsp()` para determinar si un punto está dentro de un triángulo usando coordenadas baricéntricas.

#### [CPP-03](https://github.com/loreeue/Cpps) - 100/100

Este módulo se centra en la **herencia en C++98**, aplicando los principios de programación orientada a objetos. A través de clases derivadas y herencia múltiple, se exploran conceptos como el encadenamiento de constructores, el uso de `virtual` implícito, ocultamiento de nombres y ambigüedad en la herencia.

Ejercicios:

* **Aaaaand... OPEN! (ex00):** Clase `ClapTrap` con atributos de estado (`hitPoints`, `energyPoints`, `attackDamage`) y métodos básicos (`attack`, `takeDamage`, `beRepaired`). Se imprime información detallada en cada acción y constructor/destructor.
* **Serena, my love! (ex01):** Clase `ScavTrap`, derivada de `ClapTrap`. Modifica atributos por defecto y añade el método especial `guardGate()`. Se refuerza el concepto de herencia simple.
* **Repetitive work (ex02):** Clase `FragTrap`, otra derivada de `ClapTrap`, con valores únicos y el método especial `highFivesGuys()`. Se enfatiza el constructor/destructor chaining.
* **Now it’s weird! (ex03):** Clase `DiamondTrap`, que **hereda de `ScavTrap` y `FragTrap`**. Usa herencia múltiple y atributos combinados. Implementa el método `whoAmI()` que muestra tanto su nombre como el de su base `ClapTrap`. Maneja ambigüedad de herencia y sobrescritura.

#### [CPP-04](https://github.com/loreeue/Cpps) - 100/100

Este módulo profundiza en el **polimorfismo por subtipado**, el uso de **clases abstractas**, y la simulación de **interfaces en C++98**. Se implementan jerarquías de clases con funciones virtuales puras, uso correcto de `new`/`delete`, y copias profundas para evitar errores de memoria.

Ejercicios:

* **Polimorfismo básico (ex00):** Clases `Animal`, `Dog`, `Cat` con `makeSound()` virtual. Se demuestra el polimorfismo mediante punteros a clase base. También se implementa `WrongAnimal` y `WrongCat` para ilustrar el error al omitir `virtual`.

* **Brainstorming (ex01):** Introducción de la clase `Brain`, que contiene 100 ideas. `Dog` y `Cat` manejan su propio `Brain*`. Se implementan destructores adecuados y **copias profundas** para evitar compartir memoria entre instancias.

* **Clase abstracta (ex02):** `Animal` se convierte en clase abstracta al incluir `makeSound() = 0`. Se impide instanciación directa y se mantiene la funcionalidad previa mediante clases derivadas.

* **Interfaces y recapitulación (ex03):** Sistema tipo RPG con materias mágicas (`AMateria`, `Ice`, `Cure`). Se implementan las interfaces `ICharacter` y `IMateriaSource`, y sus clases concretas `Character` y `MateriaSource`. Se prueba el uso de `clone()`, `equip()`, `use()` y la gestión correcta de memoria y copias profundas.

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
