# Projeto-Teste-5-operacoes
Teste
#include <iostream>
using namespace std;

int main() {
    float num1, num2;
    
    cout << "Escolha um número válido >";
    cin >> num1;
    
    cout << "Escolha um número válido >";
    cin >> num2;
cout << endl;
    
    
cout << "O 1° é " << (int(num1) % 2 == 0 ? "par" : "ímpar") 
 << " e o 2° é " << (int(num2) % 2 == 0 ? "par" : "ímpar") 
 << "." << endl << endl;
    
    cout << "Soma: " << num1 + num2 << endl;
    cout << "Subtração: " << num1 - num2 << endl;
    cout << "Multiplicação: " << num1 * num2 << endl;
    
    if (num2 != 0) {
        cout << "Divisão: " << num1 / num2 << endl;
    } else {
        cout <<"0 é indivisivel." << endl;
    }
    return 0;
}