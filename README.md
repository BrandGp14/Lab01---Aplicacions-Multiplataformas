# Lab01---Aplicacions-Multiplataformas

void main() {
  List<int> numeros = [1, 2, 3, 4, 5, 6];
  
  // Hallar el menor------------------------------------
  int menor = numeros[0];
  for (var numero in numeros) {
    if (numero < menor) {
      menor = numero;
    }
  }
  print('--------EJERCICIO 01----------');
  print('El menor número es: $menor');
  print('================');
  print('');

  // Hallar el mayor-------------------------------------
  int mayor = numeros[0];
  for (var numero in numeros) {
    if (numero > mayor) {
      mayor = numero;
    }
  }
  
  print('--------EJERCICIO 02----------');
  print('El mayor número es: $mayor');
  print('================');
  print('');



  // Calcular el promedio---------------------------------
  int suma = 0;
  for (var numero in numeros) {
    suma += numero;
  }
  double promedio = suma / numeros.length;
  
  print('--------EJERCICIO 03----------');
  print('El promedio es: $promedio');
  print('================');
  print('');



  // Sumar los números impares-----------------------------
  int sumaImpares = 0;
  for (var numero in numeros) {
    if (numero % 2 != 0) {
      sumaImpares += numero;
    }
  }
  print('--------EJERCICIO 04----------');
  print('La suma de los números impares es: $sumaImpares');
   print('================');

}
