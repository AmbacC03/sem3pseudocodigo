```
Algoritmo numeroascendente_descendente
	Imprimir "---Numeros ascendentes y descendentes---"
	Imprimir "Ingrese un numero"
	Leer num
	Imprimir "Operaciones disponibles: "
	Imprimir "1. Numero ascendente"
	Imprimir "2. Numero descendente"
	Imprimir "Ingrese operacion a realizar: "
	Leer opcion
	Segun opcion hacer
		1:
			Para iterador <- 1 Hasta num Con Paso 1 Hacer
				Imprimir ConvertirATexto(iterador)
			FinPara
		2: 	
			Para iterador <- 0 Hasta num Con Paso -1 Hacer
				Imprimir ConvertirATexto(iterador)
			FinPara
		De Otro Modo:
			Imprimir "Opcion incorrecta"
	FinSegun
	
FinAlgoritmo

```
