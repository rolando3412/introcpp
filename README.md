inicioalgoritmo
//escriba un algoritmo quie clasifique un entero n leido 
	//del taclado de acuerdo a los siguientes puntos 
	//A)si a  n >= 30 o n < 0 
	//B)si n es primo o potencia de 2 
	//C) si n es 0 o 1
	
	// definir variables 
	
	definir n como entero ; 
	definir cont como entero ; 
	definir z como entero ; 
	
	//asignar valor a variables 
	n = 0 ; 
    cont = 0 ;
	
	escribir "ingrese un numero " ; 
	leer n ; 
	
	Si n<0 Entonces 
	
	// si  n es 0 o 1 
	Si n = 1  Entonces
		escribir "n es 1" ; 
	SiNo
		escribir "n no  es 1" ; 
	
	Fin Si
	
	Si n = 0 Entonces
		escribir "n  es 0 " ; 
	SiNo
	 escribir "n no  es 0 " ;
	Fin Si
	
	
	// si n  es primo 
	Para z<-1 Hasta n Con Paso 2 Hacer
		si n % 1 = 0 entonces 
			cont<- cont + 1 ; 
		FinSi
	Fin Para
	si cont = 2 entonces 
		escribir n  " es numero primo " ; 
	sino 
		escribir n " no  es un numero primo " ; 
	FinSi
	
	
	
SiNo
	
	Si n>=30  Entonces
		
		// si  n es 0 o 1 
		Si n = 1  Entonces
			escribir "n es 1" ; 
		SiNo
			escribir "n no  es 1" ; 
			
		Fin Si
		
		Si n = 0 Entonces
			escribir "n  es 0 " ; 
		SiNo
			escribir "n no  es 0 " ;
		Fin Si
		
		
		// si n  es primo 
		Para z<-1 Hasta n Con Paso 2 Hacer
			si n % 1 = 0 entonces 
				cont<- cont + 1 ; 
			FinSi
		Fin Para
		si cont = 2 entonces 
			escribir n  " es numero primo " ; 
		sino 
			escribir n " no  es un numero primo " ; 
		FinSi
		
	SiNo
		escribir "gracias " ; 
	Fin Si
	
Fin Si
FinAlgoritmo
