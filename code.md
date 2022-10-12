#include <stdlib.h> 
#include <stdio.h> 

/* 1
int main() {

    printf( "Vvedite mesyac: " );
    int a;
    scanf( "%d", &a );
    switch ( a ) {
    
        case 12: case 1: case 2:
        printf("1 kvartal - zima\n");
        break;
        case 3: case 4: case 5:
        printf("«2 kvartal - vesna\n");
        break;
        case 6: case 7: case 8:
        printf("3 kvartal - leto'\n");
        break;
        case 9: case 10: case 11:
        printf( "4 kvartal - osen''\n" );
        break;
        default:
        printf( "\n Error\n" );
    }
}
*/

/* 2
int main() {

    printf( "vvedite C: " );
    int a;
    scanf( "%d", &a );
    switch(a) {
        	  case -9: printf("minus devyat"); break;
            case -8: printf("minus vocem"); break;
            case -7: printf("minus cem"); break;
            case -6: printf("minus shest"); break;
            case -5: printf("minus pyt"); break;
            case -4: printf("minus cheture"); break;
            case -3: printf("minus tri"); break;
            case -2: printf("minus dva"); break;
            case -1: printf("minus odin"); break;
            case 0: printf("nol"); break;
            case 1: printf("odin"); break;
            case 2: printf("dva"); break;
            case 3: printf("tri"); break;
            case 4: printf("chetire"); break;
            case 5: printf("pyt"); break;
            case 6: printf("shest"); break;
            case 7: printf("cem"); break;
            case 8: printf("vosem"); break;
            case 9: printf("devyat"); break;
            default: printf("\n ne to chislo \n");
		}
}
*/


/* 3
int main() {

	int year;
	float year2;	
	printf("Vvedite god: ");
	scanf("%d", &year);
	year2 = year / 12;
	year2 *= 12;
	year = year - year2;
	switch (year) {
			case 0: printf("god obez'yani\n"); break;
			case 1: printf("god petuha\n");break;;
			case 2: printf("god sobaki\n");break;
			case 3: printf("god svin'i\n");break;
			case 4: printf("god krisi\n");break;
			case 5: printf("god korovi\n");break;
			case 6: printf("god tigra\n");break;
			case 7: printf("god zayca\n");break;
			case 8: printf("god drakona\n");break;
			case 9: printf("god zmei\n");break;
			case 10: printf("god loshadi\n");break;
			case 11: printf("god ovci\n");break;
			default: printf("\n God vveden neverno\n");
		}
}
*/

/* 4
int main() {   

	  int d,m;
    printf("\n vvedite mesyats i den':");  scanf("%d", &m); scanf("%d", &d);
    if (d<32) {
    	switch(m)
    	{
	    case 1:printf("nomer dnya v godu: %d \n", d); break;
		  case 2:printf("nomer dnya v godu: %d \n", d+31); break;
		  case 3:printf("nomer dnya v godu: %d \n", d+59); break;
	    case 4:printf("nomer dnya v godu: %d \n", d+90); break;
		  case 5:printf("nomer dnya v godu: %d \n", d+120); break;
		  case 6:printf("nomer dnya v godu: %d \n", d+151); break;
	    case 7:printf("nomer dnya v godu: %d \n", d+181); break;
		  case 8:printf("nomer dnya v godu: %d \n", d+212); break;
		  case 9:printf("nomer dnya v godu: %d \n", d+243); break;
		  case 10:printf("nomer dnya v godu: %d \n", d+273); break;
		  case 11:printf("nomer dnya v godu: %d \n", d+304); break;
		  case 12:printf("nomer dnya v godu: %d \n", d+334); break;
      
      	  default:printf("oshibka, nachnite eshe raz \n");
      }
    
	}
    else {
    	printf("oshibka, nachnite eshe raz \n");
	}
    
}
*/
