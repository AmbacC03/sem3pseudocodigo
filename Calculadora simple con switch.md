```
Algoritmo Calculadorasimple_Switch
	Imprimir "--Calculadora Simple--"
	
	Escribir "Ingrese primer numero"
	Leer n1
	Escribir "Ingrese segundo numero"
	Leer n2
	Escribir "Ingrese una operacion: +,-,*,/"
	Leer operacion
	
	Si operacion == "+"| operacion == "-"| operacion == "*"| operacion == "/" Entonces
		Imprimir "Procesando: " + ConvertirATexto(n1) + " " + operacion + " " + ConvertirATexto(n2)
		Segun operacion Hacer
			"+" :
				Imprimir "Resultado: "+ ConvertirATexto(n1 + n2)
			"-" :
				Imprimir "Resultado: " n1 - n2
			"*" :
				Imprimir "Resultado: " n1 * n2
			"/" :
				Imprimir "Resultado: " n1 / n2
		FinSegun
	SiNo
		Imprimir "La operacion no es valida"
	FinSi
FinAlgoritmo
```
