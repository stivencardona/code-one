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
  for(int level = levels; level > 0; level--) {
    for(int aster = 1; aster <= level; aster++) {
      cout << "* ";
    }
    cout << "\n";
  }
}
```