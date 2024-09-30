#include <stdio.h>

int main() {
    float percentage;

    printf("Enter student percentage:");
    scanf("%f", & percentage);

if (percentage >=75 && percentage <= 100) {
    printf("The student has passed,congratulations.\n"); 
    printf("Congratulations the student will get scholarship");
} else if (percentage > 0 && percentage <75) {
    printf("The student has failed. \n");
    printf("Better luck next time.");
}  else {
    printf("Please enter a valid percentage between 0 to 100%%.\n");
}

return 0;
}
