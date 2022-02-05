# Actidad 2

## Se debe realizar una programa que podamos verificar en que estación nos encontramos según el mes. 


Lleve a cabo las siguientes acciones en un editor de textos en un nuevo archivo con extensión js. No es necesario entregar un archivo html.
- Crear una variable llamada mes y que tenga asignado por defecto el valor 10.
- Crear un programa que verifique si el valor de mes está entre 12 y 2 (12, 1 o 2), entonces que imprima en pantalla “es invierno”, si el valor de mes está entre 3 y 5, que imprima en pantalla “es primavera”, si el valor de mes se encuentra entre 6 y 8 que imprima en pantalla “es verano” y si se encuentra entre 9 y 11 que imprima en pantalla “es otoño”.
- Al finalizar debe imprimir en pantalla un mensaje que indique su número de carné y su nombre completo.

- Codigo del programa
var mes = 10
if (mes == 12 || mes == 1 || mes == 2){
   alert("Es invierno")
   alert ("No.Carnet:14001101/Jairo Estuardo Gonzalez Paz")
}else if (mes == 3 || mes == 4 || mes == 5){
  alert("Es primavera")
  alert ("No.Carnet:14001101/Jairo Estuardo Gonzalez Paz")
}else if (mes == 6 || mes == 7 || mes == 8){
  alert("Es verano")
  alert ("No.Carnet:14001101/Jairo Estuardo Gonzalez Paz")
}else if (mes == 9 || mes == 10 || mes == 11){
  alert("Es otoño")
  alert ("No.Carnet:14001101/Jairo Estuardo Gonzalez Paz")
}
