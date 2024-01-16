# Version de la prueba
Version 1.2.2
# Cabeceras
# cabecera h1
## cabecera h2
### cabecera h3
#### cabecera h4
##### cabecera h5
###### cabecera h6

# Underlines

Underline 1
--------
Underline 2
===========

# Formatos de enfasis
- ~~ALT~~ 
- **HOLA**
 - *HOLA*

# Listas
1. Esto es un item
1. Esto es un item
1. Esto es un item
-  Esto es un item
- Esto es un item
- Esto es un item
+ Esto tambien es un item

# Links
- [Este link es de google](http://www.google.com)
- [Este link es del index](index.html)

# Imagenes
![Imagen de prueba](https://images.unsplash.com/photo-1595433707802-6b2626ef1c91?ixlib=rb-4.0.3&q=85&fm=jpg&crop=entropy&cs=srgb)

# Code snippets
Código en C++
```C++

#include <iostream>
using std::cout;
using std::cin;
using std::endl;
void mostrarArreglo(const int[], int); 
void ordenarArreglo(int[], int); 
void intercambiar(int&, int&); 
int main()
{
  const int tamano = 15;
  int arreglo[tamano] = {25,17,13,16,41,32,12,115,95,84,54,63,78,21,10};
  cout << "Arreglo antes de ordenarse: " <<endl;
  mostrarArreglo(arreglo,tamano);
  cout << "Arreglo despues de ordenarse: " <<endl;
  ordenarArreglo(arreglo,tamano);
  mostrarArreglo(arreglo,tamano);
  cout << "Fin del programa :)" << endl;
  return 0;
}

void mostrarArreglo(const int arreglo[], int tamano)
{
  for (int i = 0 ; i < tamano ; i++)
    cout << "arreglo["<< i << "]=" << arreglo[i]<< endl;
}
void ordenarArreglo(int arreglo[], int tamano)
{
  for (int i = 0; i<tamano-1 ; i++)
    for (int j = 0; j<tamano-1 ; j++)
      if(arreglo[j] < arreglo[j+1])
 intercambiar(arreglo[j],arreglo[j+1]);
}
void intercambiar(int &a, int &b)
{
  int tmp = b;
  b = a;
  a = tmp;
} 
```
# Tablas
|Columna 1 |Columna 2 |Columna 3 |
|----------|----------|----------|
1 | 2 | 3 |
3 | 1 |2 |
# Citas
Esto es una prueba para ver el uso de las citas:
> Esta es una cita

Texto ....
> Esta es otra cita
# Lineas divisoras
Primer texto de prueba

---
Segundo texto de prueba

*** 
# Saltos de linea
Este es un texto de prueba

Este es otro texto de prueba

Texto.....