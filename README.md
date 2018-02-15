# HesapMakinas-
#include <stdio.h>
#include <math.h>
void carpma(float sayi1 , float sayi2);
float cikarma(float sayi1,float sayi2);
main()
{
	float sayi1=3.0;
	float sayi2=5.0;
	carpma(sayi1 , sayi2);
 cikarma(sayi1,sayi2);	
}

  void carpma(float sayi1 ,float sayi2)
{
	float carpim=0.0;
	carpim = sayi1*sayi2;
	printf("%f",carpim);
}
float cikarma(float sayi1,float sayi2)
{
float cikarma=0.0;
cikarma = (sayi1-sayi2);
printf("%f",cikarma);


}
