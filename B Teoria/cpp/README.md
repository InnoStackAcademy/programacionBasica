# El lenguaje C++  

C++ es una extensión de C creada por Bjarne Stroustrup en los años 80. Este lenguaje añadió la **programación orientada a objetos (POO)** a las capacidades de C, haciéndolo más poderoso para crear sistemas complejos y aplicaciones escalables.

## **Tema 1: Introducción a C++**
- Historia y características principales.
- **Diferencias con C.**
- Configuración del entorno:
  - Compiladores: `g++`, MinGW, Clang.
  - IDEs: VSCode, Code::Blocks, CLion.
- Primer programa: "Hola, Mundo".
```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hola, Mundo!" << endl;
    return 0;
}
```
- Estructura básica:
  - `#include`, `main()`, flujo del programa.

**Práctica:**
1. Escribir varios programas básicos que impriman mensajes en consola.

---

## **Tema 2: Fundamentos del Lenguaje**
- **Tipos de datos y operadores:**
  - `int`, `float`, `double`, `char`, `bool`.
  - Operadores aritméticos, relacionales, lógicos, bit a bit.
- **Entrada y salida con `cin` y `cout`.**
- **Variables y constantes.**
- **Conversiones implícitas y explícitas (casting).**

**Práctica:**
1. Crear un programa que solicite datos al usuario y realice operaciones matemáticas.
2. Escribir un programa que determine si un número es par o impar.

---

## **Tema 3: Control de Flujo**
- **Condicionales:**
  - `if`, `else if`, `else`, `switch`.
- **Bucles:**
  - `for`, `while`, `do-while`.
- **Ruptura y continuaciones:**
  - `break`, `continue`.
- **Rangos (`for` moderno en C++11).**

**Práctica:**
1. Crear un programa que calcule el factorial de un número.
2. Escribir un programa que genere un patrón de asteriscos en forma de pirámide.

---

## **Tema 4: Funciones**
- **Declaración y definición.**
- **Paso de parámetros:**
  - Por valor, por referencia y por puntero.
- **Sobrecarga de funciones.**
- **Funciones recursivas.**

**Práctica:**
1. Implementar una función que calcule la potencia de un número.
2. Escribir una función recursiva para resolver el problema de la Torre de Hanói.

---

## **Tema 5: Programación Orientada a Objetos (POO)**
- **Clases y objetos:**
  - Declaración, métodos, atributos.
- **Constructores y destructores.**
- **Encapsulamiento, herencia y polimorfismo.**
- **Sobrecarga de operadores.**
- **Uso de `this` y referencias.**

**Práctica:**
1. Crear una clase `Persona` con atributos básicos y métodos para mostrar información.
2. Escribir una clase `Rectangulo` que calcule el área y perímetro.

---

## **Tema 6: Arreglos, Vectores y Cadenas**
- **Arreglos estáticos.**
- **Vectores dinámicos (`std::vector`).**
- **Cadenas (`std::string` vs. `char[]`).**
- **Iteradores y algoritmos básicos con `std::vector`.**

**Práctica:**
1. Crear un programa que ordene un arreglo de números.
2. Implementar una función que determine si una palabra es palíndromo.

---

## **Tema 7: Punteros y Memoria Dinámica**
- **Punteros básicos y aritmética de punteros.**
- **Uso de `new` y `delete`.**
- **Punteros inteligentes (`std::unique_ptr`, `std::shared_ptr`).**
- **Relación entre punteros y arreglos.**

**Práctica:**
1. Escribir un programa que use punteros para invertir un arreglo.
2. Implementar un programa que gestione la memoria de una lista dinámica.

---

## **Tema 8: Manejo de Archivos**
- **Flujo de entrada y salida (`fstream`).**
- **Lectura y escritura en archivos.**
- **Manejo de archivos binarios.**

**Práctica:**
1. Crear un programa que lea y escriba un archivo de texto con datos de estudiantes.
2. Implementar un sistema de registro de productos usando archivos binarios.

---

## **Tema 9: Plantillas y STL (Standard Template Library)**
- **Introducción a plantillas:**
  - Funciones y clases genéricas.
- **Uso de STL:**
  - Contenedores (`vector`, `list`, `map`, `set`).
  - Algoritmos (`sort`, `find`, `count`).
- **Iteradores y lambda expressions.**

**Práctica:**
1. Crear una función plantilla para buscar el máximo de dos valores.
2. Usar un `std::map` para implementar una agenda telefónica.

---

## **Tema 10: Manejo de Excepciones**
- **Try, Catch y Throw.**
- **Clases de excepciones personalizadas.**

**Práctica:**
1. Escribir un programa que maneje divisiones por cero con excepciones.
2. Crear una clase que valide datos y lance excepciones en caso de errores.

---

## **Tema 11: Programación Avanzada**
- **Multithreading:**
  - Uso de hilos con `std::thread`.
- **Operaciones con ficheros grandes y flujo de datos.**
- **Interacción con bibliotecas externas.**

**Práctica:**
1. Implementar un programa que calcule la suma de elementos de un vector usando múltiples hilos.
2. Crear un programa que consuma una API simulada y muestre resultados en tiempo real.

---

## **Tema 12: Proyecto Final**
- **Planificación y diseño:**
  - Elegir un proyecto que integre múltiples conceptos aprendidos.
- **Proyectos sugeridos:**
  1. Juego de consola como "Adivina el Número".
  2. Sistema de gestión de inventario.
  3. Simulador de banco con operaciones de cuentas.