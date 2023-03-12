---
title: "Ciclos"
date: 2023-03-11
summary: "Los ciclos son estructuras basicas de los lenguajes de programcion estos nos permiten repetir un conjunto instrucciones"
description: "Los ciclos son estructuras basicas de los lenguajes de programcion estos nos permiten repetir un conjunto instrucciones"
tags: ["ciclos", "greedy"]
author: "Stiven Cardona"
draft: false
---

## Ejercicios

1. Dado un numero `n` mostrar los numeros de `1` hasta `n`
2. Dado un numero `n` mostrar los numeros pares de `1` hasta `n` 
3. Dado un numero `n` mostrar los numeros impares de `1` hasta `n`
4. Dado un numero `n` decir si ese numero `n` es primo
5. Dado un numero `n` (el numero de niveles) imprimir la siguiente figura:
Ejemplo para `n = 5`
```bash
*
* *
* * *
* * * *
* * * * *
```
6. Dado un numero `n` (el numero de niveles) imprimir la siguiente figura:
Ejemplo para `n = 5`
```bash
* * * * * 
* * * *
* * *
* * 
* 
```
7. Dado un numero `n` (el numero de niveles) imprimir la siguiente figura:
Ejemplo para `n = 5`
```bash
        * 
      * * *
    * * * * *
  * * * * * * * 
* * * * * * * * *
```
8. Dado un numero `n` (el numero de niveles) imprimir el triagulo de pascal:
Ejemplo para `n = 5`
```bash
1 
1 2 1
1 3 3 1
1 4 6 4 1 
1 5 10 10 5 1
```

## Pistas

- Implementacion **[1]**
- El residuo de la division entre `2` de un numero `x` es `0`, si y solo si `x` es par y `1` si y solo si `x` es impar **[2,3]**

## Soluciones

Las soluciones a estos problemas estan escritas en c++ para compilarlas tienes varias opciones:

1. Descargar a tu computador el compilador y ejecutar un comando como `g++ -std=c++11 <name-file.cpp>`

2. Usar una herramienta online como [esta](https://www.programiz.com/cpp-programming/online-compiler/)

3. Si eres usuario windows tambien podras descardar `codeblocks` un editor para compilar codigo en `c` y `cpp`

- [Ejercicio 1]({{< ref "one" >}})
- [Ejercicio 2]({{< ref "two" >}})
- [Ejercicio 3]({{< ref "three" >}})
- [Ejercicio 4]({{< ref "four" >}})
- [Ejercicio 5]({{< ref "five" >}})
- [Ejercicio 6]({{< ref "six" >}})
- [Ejercicio 7]({{< ref "seven" >}})
<!-- - [Ejercicio 8]({{< ref "/solutions/ciclos/one" >}}) -->