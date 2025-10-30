# pgcd-
programme c pour calculer le pgcd

#include <stdio.h>
int main() {
    int a,b,temp;
    printf("veuillez entrer deux nombres entiers : ");
    scanf("%d %d", &a , &b );
    while(b!=0){
            temp=b;
            b=a%b;
            a=temp;
            }
            printf("le pgcd est : %d", a);
            if(a=1)
            printf("les deux nombres sont premiers entre eux")
            return 0;
}
