---
title: "Es primo"
summary: "Solucion ejercicio 4"
description: "Solucion ejercicio 4"
date: 2023-03-12
tags: ["ciclos"]
draft: true
---
```cpp
#include <iostream>

using namespace std;

int main() {
  int n; cin >> n;
  int divs = 0;
  for (int i = 2; i <= sqrt(n); i++) {
    divs += ( n % i == 0 );
  }
  if(divs) {
    cout << n << " no es primo\n";
  } else {
    cout << n << " es primo\n";
  }
  return 0;
}
```