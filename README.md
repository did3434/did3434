#include <iostream>

int addition(int a, int b) {
    return a + b;
}

int main() {
    int resultat = addition(2, 3);
    std::cout << "La somme est : " << resultat << std::endl;
    return 0;
}
