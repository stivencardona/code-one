---
title: "Solucion ejercicio 1"
date: 2023-03-12
tags: ["ciclos"]
---
```cpp
#include <iostream>

using namespace std;

int main() {
  int n; cin >> n;
  for (int i = 0; i <= n / 2; i++) {
    cout << 2 * i + 1<< "\n";
  }
  return 0;
}
```