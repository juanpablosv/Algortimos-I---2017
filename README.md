// AreaTriangulo.cpp : Defines the entry point for the console application.
// Nombre:AreaTriangulo				
// Autor: Juan Pablo Suaznabar
// Fecha: 15/02/2017

// Declarar librerias
#include "stdafx.h"  //Libreria del Visual C++ stdio
#include "conio.h"   //Para manejar la entrada y getch()
#include <iostream>  // Entrada y salida cin, cout

// Declara el teclado y el monitor como la salida y entrada estandard
using namespace std;

// El cuerpo principal del programa
void main()
{
   float area,base,altura; // Declaración de variables
   // Ingreso de datos con mensaje y solicitud de datos
   cout<<"Ingrese base: ";
   cin>>base;
   if(base<=0){
	   cout<< " Error";
   }else{
   cout<<"Ingrese altura: ";
    cin>>altura;
   if(altura<=0){
	   cout<< " Error";
   }else{
   // Proceso: Calculo     // los operadores validos 
   area=(base*altura)/2;
   // Salida de la respuesta o resultado
   cout<<"El area es: "<<area;
     }
   }

   getch(); // Detiene la pantalla
}
//Finaliza el cuerpo principal
