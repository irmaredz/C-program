#include <stdio.h>
#include <stdlib.h>

int main(){
     int broj,k,zbir;
     float srednja;
     k=0; zbir=0;
     do {
         scanf ("%d",&broj);
         if (broj!=-1 && (broj<1 || broj>100)) {printf("Broj nije u opsegu 1-100! Unesite ponovo\n"); continue;}
         if (broj%3==0) {k++; zbir=zbir+broj;}
     } while(broj!=-1);
     if (k>0) {
         srednja=zbir/k;
     } 
     else 
        srednja=0.00;
     printf ("Srednja vrijednost je: %.2f",srednja);
     return 0;
    }
