Proceso sin_titulo
	Definir opcion_cal, contador_suma, contador_resta Como entero;
	Definir num1, num2, resultado_suma, resultado_resta, contador_resultado_suma, contador_resultado_resta Como Entero;
	contador_suma = 0;
	contador_resta = 0;
	opcion_cal = 1;
	Mientras opcion_cal <> 3 Hacer
		Escribir "1. sumar";
		Escribir "2. restar";
		Escribir "3. Salir";
		Leer opcion_cal;
		Segun opcion_cal Hacer
			1:
				Escribir "Suma";
				Escribir "Ingrese el primer numero";
				Leer num1;
				Escribir "Ingrese segundo numero";
				Leer num2;
				resultado_suma = num1 + num2;
				Escribir "El resultado es = ", resultado_suma;
				contador_suma = contador_suma + 1;
				
				
			2:
				Escribir "Resta";
				Escribir "Ingrese el primer numero";
				Leer num1;
				Escribir "Ingrese segundo numero";
				Leer num2;
				resultado_resta = num1 - num2;
				Escribir "El resultado es = ", resultado_resta;
				contador_resta = contador_resta + 1;
			3:
				Escribir "saliendo";
		
		FinSegun
	FinMientras
	Escribir "Numero de sumas realizadas: ", contador_suma;
	Escribir "Numero de restas: ", contador_resta;
