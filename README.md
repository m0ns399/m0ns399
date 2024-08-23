- 👋 Hi, I’m @m0ns399
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
m0ns399/m0ns399 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <iostream>
using namespace std;
int main() {
    double horasTrabajadas, tarifaPorHora, salario;
// Solicitar al usuario que ingrese las horas trabajadas y la tarifa por hora
    cout << "Ingrese la cantidad de horas trabajadas: ";
    cin >> horasTrabajadas;
    cout << "Ingrese la tarifa por hora: ";
    cin >> tarifaPorHora;
// Verificar si las horas trabajadas son mayores a 50
    if (horasTrabajadas > 50) {
        double horasExtras = horasTrabajadas - 50;
        double tarifaExtra = tarifaPorHora * 1.4;  // Incremento del 40%
        salario = (50 * tarifaPorHora) + (horasExtras * tarifaExtra);
    } else {
        salario = horasTrabajadas * tarifaPorHora;
    }
// Mostrar el salario calculado
    cout << "El salario total del trabajador es: $" << salario << endl;
return 0;
}
