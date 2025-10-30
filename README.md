# pgcd-
programme c pour calculer le pgcd

#include <stdio.h>
int main() {
    int a,b,temp;
    printf("veuillez entrer deux nombres entiers : ");
    //affichage de ce message pour entrer deux nombres entiers
    scanf("%d %d", &a , &b );
    //lecture de deux nombres
    while(b!=0){
            temp=b;
            b=a%b;
            a=temp;
            }
            //la boucle arrête lorsque b=0
            printf("le pgcd est : %d", a);
            if(a=1)
            printf("les deux nombres sont premiers entre eux")
            return 0;
}
