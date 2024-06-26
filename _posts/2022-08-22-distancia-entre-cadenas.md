---
layout: post
categories:
  - Proyecto
tags:
  - Estructuras de datos
last_modified_at: 2022-08-22T14:25:52-06:00
---

Este proyecto de Java proporciona una implementación del algoritmo de distancia de edición para calcular la distancia entre dos cadenas. El repositorio está disponible en <a href= "https://github.com/javier-mdcg/DstanciaEntreCadenas">GitHub</a>.

El algoritmo de distancia de edición, también conocido como distancia de Levenshtein, es una medida de la cantidad mínima de operaciones necesarias para transformar una cadena en otra. Estas operaciones pueden ser inserciones, eliminaciones o sustituciones de caracteres.

## Uso

Puedes utilizar esta funcionalidad en tus propios proyectos de Java siguiendo estos pasos:

1. Incluye la clase `distanciaEntreCadenas` en tu proyecto Java.
2. Llama al método `calculaDistancia(String s1, String s2)` proporcionando las dos cadenas que deseas comparar. Este método devolverá la distancia entre las cadenas.

```java
int distancia = distanciaEntreCadenas.calculaDistancia("cadena1", "cadena2");
System.out.println("La distancia entre las cadenas es: " + distancia);
```

## Ejemplo

```java
public class Main {
    public static void main(String[] args) {
        // Ejemplo de uso
        System.out.println(distanciaEntreCadenas.calculaDistancia("hola", "holse")); // Salida: 2
    }
}
```