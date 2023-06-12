```
Algoritmo OpcionMultiple
	Imprimir "---Opcion Multiple---"
	Imprimir "Opciones  Utilizables"
	Imprimir "1. Suma de dos cifras"
	Imprimir "2. Imprimir dia de la semana"
	Imprimir "3. Calcular la longitud de texto"
	Imprimir "Ingrese la eleccion: "
	Leer  opcion
	Segun opcion hacer
		"1":
			Imprimir "opcion 1.Suma de dos cifras"
			Imprimir "Ingrese primer dato"
			Leer num1
			Imprimir "Ingrese segundo dato"
			Leer num2
			Imprimir "Resultado: " + ConvertirATexto(num1 + num2)
		"2":
			Imprimir "opcion 2.Imprimir dia de la semana"
			Imprimir "Ingrese el dia de la semana en numeros (1-7)"
			Leer dia
			Segun dia hacer
					"1": 
						Imprimir "Lunes"
					"2":	
						Imprimir "Martes"
					"3":	
						Imprimir "Miercoles"
					"4":	
						Imprimir "Jueves"
					"5":	
						Imprimir "Viernes"
					"6":
						Imprimir "Sabado"
					"7":
						Imprimir "Domingo"
				De Otro Modo:
					Imprimir "¡Dia incorrecto!"
			FinSegun
		"3":
		Imprimir "Opcion 3.Calcular longitud de texto"
		Imprimir "Ingrese un texto"
		Leer cadena
		Imprimir "Resultado: "+ ConvertirATexto(Longitud(cadena))
	De Otro Modo:
		Imprimir "¡Opcion incorrecta!"
FinSegun
	
FinAlgoritmo

```
