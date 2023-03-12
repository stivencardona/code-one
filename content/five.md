---
title: "Triangulo"
date: 2023-03-12
summary: "Solucion ejercicio 5"
description: "Solucion ejercicio 5"
tags: ["ciclos"]
draft: true
---
```cpp
#include <iostream>

using namespace std;

int main() {
  int levels; cin >> levels;
  for(int level = 1; level <= levels; level++) {
    for(int aster = 1; aster <= level; aster++) {
      cout << "* ";
    }
    cout << "\n";
  }
}
```