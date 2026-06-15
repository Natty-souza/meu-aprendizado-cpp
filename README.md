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
