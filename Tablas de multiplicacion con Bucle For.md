```
Algoritmo Tablas_de_multiplicar_CBucle
	Imprimir "---Tablas de multiplicar---"
	Imprimir "Ingrese la tabla a calcular: "
	Leer cifra
	Imprimir "Resultado de tabla de " + ConvertirATexto(cifra)
	Para iterador <- 1 Hasta 10 Con Paso 1 Hacer
		Imprimir ConvertirATexto(cifra) ' *  ' + ConvertirATexto(iterador) + ' = ' ConvertirATexto(cifra * iterador)
	Fin Para

FinAlgoritmo
```
