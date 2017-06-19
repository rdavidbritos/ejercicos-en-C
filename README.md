# Ejercicos-en-C
Ejercicios basicos en C
//ejercicio: Varias empresa de rating de televisión (4 cuatro) realizan encuestas hogareñas sobre qué programa están viendo en los distintos hogares
Se sabe que existen 5 canales de aire y se divide al día en 8 franjas horarias
Cada vez que se realiza una encuesta se tienen los siguientes datos
•	Nro de encuesta 
•	Canal
•	Franja horaria
•	Dia (1 a 7 )
•	Empresa encuestadora

Los datos finalizan con nro de encuesta igual a 0

Se desea saber
1.	¿Qué canal tuvo en total el mejor rating semanal?
2.	¿Qué porcentaje representa el rating de cada franja sobre el total encuestado?
3.	Si a la empresa encuestadora se le paga $2 por cada encuesta realizada, ¿cuánto cobrara? 
4.	¿Cuantas encuestas se realizaron cada día?
5.	¿Todas las empresas encuestadoras realizaron encuestas?

#include <stdio.h>

int main ()
{
	
	int nro_canal;
	int comision;
	int cant_ent; //cantidad de canales entrevistados
	
	comision=2; //$2 pesos
	int entr=nro_canal+comision;
	
	nro_canal>=5;
	
	printf ("Seleccione un canal \n", nro_canal);
	scanf ("%d", &nro_canal);
	
	if (nro_canal=1){
	
	printf ("Canal de 8 a 12 hs\n", nro_canal);
	
	printf ("La comision es de: %d ", entr);
}


	
	return 0;	
		
	}
