Algoritmo calificaciones
	definir parcial_1, parcial_2, participación, parcial_final Como Real
	definir primerparcial, segundoparcial, participar, parcialfinal Como real
	
	escribir "ingrese la calificación del parcial_1 "
	leer parcial_1
	
	escribir "ingrese la calificación del parcial_2 "
	leer parcial_2
	
	escribir "ingrese la calificación de la participación "
	leer participación
	
	escribir "ingrese la calificación del parcial_final "
	leer parcial_final
	
	definir suma, promedio Como real
	primerparcial = 0.25
	segundoparcial = 0.25
	participar = 0.20
	parcialfinal = 0.30
	
	suma = parcial_1*primerparcial + parcial_2*segundoparcial + participación*participar + parcial_final*parcialfinal
	promedio = suma
	
	escribir "El promedio ponderado del curso es ", promedio
	
FinAlgoritmo

