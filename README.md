WstepLabo3
==========


#include<stdio.h>
        int main () {
        int n,i;
        double liczba;
        printf("kol.1|kol.2|kol.3\n");
        printf("------+------+------\n");
        scanf("%i", &n);
        for(i=0;i<n;i++) {
scanf("%lf", &liczba);
        if(i%3==2)
                printf("%6.2lf\n", liczba);
        else
                printf("%6.2lf |", liczba);
}
printf("\n");
}


#include<stdio.h>
    int main () {
        int i,j, wartosc;

for(i = 0; i <= 9; i++){
 for(j = 0; j <= 9; j++){

 wartosc = i*j;
 //wypisujesz pozycje na ekran
 printf("%2i ",wartosc);
 }
//nowa linia
printf("\n");
} }
