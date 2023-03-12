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
  int divs = 0;
  for (int i = 2; i <= sqrt(n); i++) {
    divs += ( n % i == 0 );
  }
  if(divs) {
    cout << n << " is not prime\n";
  } else {
    cout << n << " is prime\n";
  }
  return 0;
}
```