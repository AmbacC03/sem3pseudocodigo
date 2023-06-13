```
Algoritmo Tablas_de_multiplicar
	Imprimir "----Tablas_de_Multiplicar----"
	numeroUsuario = 0
	Imprimir "Ingrese la tabla a calcular: "
	Leer numeroUsuario
	Imprimir "*Calculo de la tabla del "+ ConvertirATexto(numeroUsuario)+ "*"
	contadorTabla = 1
	Mientras contadorTabla <= 10 Hacer
		Imprimir numeroUsuario, "x" , contadorTabla, " = ", contadorTabla * numeroUsuario
		contadorTabla = contadorTabla + 1
	FinMientras
FinAlgoritmo
```
