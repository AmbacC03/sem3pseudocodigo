```
Algoritmo CalculadoraDo_While
	Imprimir "----Calculadora Simple----"
	Repetir
		Imprimir "Ingrese primer numero"
		Leer num1
		Imprimir "Ingrese segundo numero"
		Leer num2
		Imprimir "Ingrese una operacion: +,-,*,/"
		Leer operacion
		Si operacion == "+" | operacion == "-" | operacion == "*" | operacion == "/" Entonces
			Imprimir "Procesando: "+ ConvertirATexto(num1) + " " + operacion + " " + ConvertirATexto(num2)    
			Segun operacion Hacer
				"+":
					Imprimir "Resultado: " + ConvertirATexto(num1+num2)
				"-":	
					Imprimir "Resultado: " + ConvertirATexto(num1-num2)
				"*":	
					Imprimir "Resultado: " + ConvertirATexto(num1*num2)
				"/":	
					Imprimir "Resultado: " + ConvertirATexto(num1/num2)
			FinSegun
		SiNo
			Imprimir "La operacion no es valida"
		Fin Si
		Imprimir "Desea continuar con otra operacion? Si / No"
		Leer continuar
	Hasta Que continuar == "no" | continuar == "no"

FinAlgoritmo

```
