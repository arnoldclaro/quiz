03 Validador de Contraseñas
Instrucción:
Desarrolla un programa que valide si una contraseña ingresada por el usuario cumple con los siguientes criterios de seguridad:
Debe tener al menos 8 caracteres
Debe contener al menos una letra mayúscula
Debe contener al menos una letra minúscula
Debe contener al menos un número
Debe contener al menos un carácter especial (@, #, $, %, &, *)
El programa debe indicar cuáles criterios no se cumplen.
Nota: Acá te dejo una ayuda.
(c == '@' || c == '#' || c == '$' || c == '%' || c == '&' || c == '*')

                                                 Analisis del problema                                                            

lo primero que debemos hacer es pedirle al usuario que ingrese una contraseña."para esto implementamos un scanner"

VARIABLES:
mayuscula
miniscula
numero
caracter especial

al momento de que el usuario ingrese la contraseña el programa va amalizar los datos ingresados

la contraseña pasa por unos filtros los cuales son:

1. que la contraseña cuente con minimamente 8 caracteres. (si la contraseña no contiene los 8 caracteres el programa va alanzarque la contraseña no cumple con el primer requisito )

2. que la contraseña cuente con una mayuscula. (si no cuenta con una mayuscula pues la contraseña no sera validada)

3. que la contraseña cuente con una miniscula. (si esta no cuenta con una minuscula no sera validada)

4 que la contraseña cuente con un mumero. (si esta no cuenta con un numero no sera validada)

5. que la contaseña cuente con un caracter especial. (si esta no cuenta con un caracter especial no sera validada)

para que cada variable utlizada en el programa valide o verifique si la contraseña cumple o no cumple con los requsitos tenemos que utilizar (if)

bueno si la contraseña ingresada cumple con los requisitos no va a marcar o a detectar que se presenta un proble en ella 

fin.