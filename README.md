# juego-al-azar
es un tipo de juego de apustas 
// Juego simple que pide al usuario que adivine un numero en 10 intentos
		intentos<-9;
		num_secreto <- azar(100)+1;
		
		escribir"adivine el numero (de 1 a 100):";
		leer num_ingresado;
		mientras num_secreto<> num_ingresado y intentos>0 Hacer
			si num_secreto>num_ingresado Entonces
				Escribir "muy bajo";
			SiNo
				escribir "muy alto"
				
			FinSi
			Escribir " le quedan ", intentos," intentos: ";
			Leer num_ingresado;
			intentos = intentos-1;
			
			
		FinMientras
		si intentos =0 Entonces
			escribir "el numero era:",num_secreto;
		SINO
			Escribir " exacto! usted adivino en ",11- intentos," intentos.";
			
		FinSi
FinAlgoritmo
