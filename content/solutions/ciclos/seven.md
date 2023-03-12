---
title: "Solucion ejercicio 1"
date: 2023-03-12
tags: ["ciclos"]
---
```cpp
#include <iostream>

using namespace std;

int main() {
  int levels; cin >> levels;
  for(int level = 1; level <= levels; level++) {
    for(int espacios = 1; espacios <= (levels - level); espacios++) {
      cout << "  ";
    }
    for(int aster = 1; aster <= (2*level - 1); aster++) {
      cout << "* ";
    }
    cout << "\n";
  }
}
```