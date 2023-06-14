```
Algoritmo Saludos
	Imprimir "---Saludos---"
	Definir continuar Como Cadena
	Definir cantidadSaludos Como Entero
	cantidadSaludos <- 0
	continuar <- "Si"
	Mientras continuar == "Si" Hacer
		Imprimir "Ingrese la hora actual (0-23): "
		Leer hora 
		Si hora <= 12 Entonces
			Imprimir "¡Buenos días!"
		SiNo
			Si hora <= 18
				Imprimir "¡Buenas tardes!"
			SiNo
				Imprimir "¡Buenas noches!"
			FinSi
		FinSi
		
		cantidadSaludos <- cantidadSaludos + 1
		Imprimir "Desea continuar? si/no"
		Leer continuar
	FinMientras
	Imprimir "Cantidad de saludos realizados: " + ConvertirATexto(cantidadSaludos)
FinAlgoritmo
```
