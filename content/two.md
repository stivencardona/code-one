---
title: "Pares"
summary: "Solucion ejercicio 2"
description: "Solucion ejercicio 2"
date: 2023-03-12
tags: ["ciclos"]
---
```cpp
#include <iostream>

using namespace std;

int main() {
  int n; cin >> n;
  for (int i = 1; i <= n / 2; i++) {
    cout << 2 * i << "\n";
  }
  return 0;
}
```