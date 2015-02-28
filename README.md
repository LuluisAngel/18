# 18
Here's the code

      #include <iostream>
      
      using namespace std;
      // Luis Angel Aguilar Carrillo A01225421
      int main (){
      
      	int x;
      
      	cout << "Introduce un numero" << endl;
      	cin >> x;
      	
      	if (x!=0){   // Cuando el numero es diferente a CERO
      
      		if (x>0){   // Si el numero es mayor a CERO, imprime lo siguiente:
      			cout << "El numero es positivo" << endl;
      		}
      
      			else if (x<0){ 	// Si el numero es menor a CERO, imprime lo siguiente.
      				cout << "El numero es negativo" << endl;
      			}
      
      	}
      
      		else { //La unica opción que queda es que el numero sea CERO 
      
      			cout << "El numero es CERO." << endl;
      		}
      		
      
      
      
      	return 0;
      }
