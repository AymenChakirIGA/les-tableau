// les-tableau
/* Tableu est un variable qui peut se compose par toute les type des variable (entier , reel ....) 
Et les tableau commance par l'indice 0 et termine par max-1 , si on a un tableau de 10 case , alors les indice vas de 0 a 9.
-Declaration : type nom[N];  (avec N est l'indice max)
-Exemple :  int t[10]; || float B[N]; 
                      ||                    
                      ||   int N=10 ;
                      
                      
-Remplissage / Affichage : on peut remplire ou afficher une case du tableau par l'utilisation des indices , ou tous le tableau on utilison les boucles 
- exemple 1 : scanf(t[1]);
              printf(t[1]);
-exemple 2 :
*/
#include<stdio.h>
#include<stdlib.h>
int main ()
{
  int t[N] ;
  int N , i; // N : indice max ; i : indice incremonter par la boucle
  scanf ("%d" , &N) ; 
  // pour le tableau c'est mieu d'utilise For , parce que on sait le max 
  for (i=0 ; i<N ; i++)
  {
    scanf("%d" , &t[i]); // Remplissage
  }
   for (i=0 ; i<N ; i++)
  {
    printf("%d" , t[i]); // Affichage
  }
  system ("pause");
  return 0;
}
