#include <iostream>


int main() {
    double distancia_operador = 1.5; 
    
    if (distancia_operador < 1.0) {
        std::cout << "ALERTA: Operador muito proximo! PARAR ROBO IMEDIATAMENTE!" << std::endl;
    } else {
        std::cout << "Seguranca OK. Robo operando normalmente." << std::endl;
    }
    
    return 0;
}


markdown### Lógica Nível 2: Adicionando alerta moderado com else if

```cpp
#include <iostream>

int main() {
    double distancia_operador = 1.8;
    // ... resto do código ...
}
```
#include <iostream>

int main() {
    double distancia_operador = 1.8;
    
    if (distancia_operador < 1.0) {
        std::cout << "ALERTA MAXIMO: Parar robo imediatamente!" << std::endl;
    } 
    else if (distancia_operador < 2.5) {
        std::cout << "ALERTA MODERADO: Reduzir velocidade do robo para 50%." << std::endl;
    } 
    else {
        std::cout << "Seguranca OK. Robo em velocidade maxima." << std::endl;
    }
    
    return 0;
}

