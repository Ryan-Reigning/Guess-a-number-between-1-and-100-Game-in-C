<!-- # Guess-a-number-between-1-and-100-Game-in-C -->
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    // Write C code here
    int number, guess, j;
    srand(time(NULL));
    
    number = rand() % 100;
    
    printf("%d\n",  number);
    
    printf("Guess the number\n");
    
    for(j = 0; j = number; j++){
    scanf("%d", &guess);
    if(guess > number){
        printf("Lower number please!\n");
    }else if(guess < number){
        printf("greater  number please!\n");
    }else{
        printf("Congratulations you guessed it!\n");
    }
    }
    
    return 0;
}
