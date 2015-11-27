#include <stdio.h>
  
int main() {
  
    int a, b, c;
     
     scanf("%d %d" ,&a, &b);
     if(a >= b) // Se a hora inicial do jogo for maior  ou igual a do final.
     {
     c=(b + 24)-a; // o resultado será a hora inicial do jogo mais 24 horas, menos a hora final, para que assim possa ser caulculado o horario se o jogo durar mais de um dia.
     printf("O JOGO DUROU %d HORA(S)\n", c); // Resultado impresso na tela.
      
     }else{ // Se não.
     c=b-a; // Resultado será hora final subtraido pela hora inicial do jogo.
     printf("O JOGO DUROU %d HORA(S)\n", c);
      
} system("pause"); }
