# EX-NO-6-Pseudo-Random-Number  

# DATE:
# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library
# ALOGRITHM:
1. Including all necessary Header files.    
2. Input the number of random numbers and range.  
3. Seed the random number generator.     
4. Initialize a loop.    
5. Generate the Random Numbers.   
6. Print the random numbers.   
# PROGRAM:
```
DEVELOPED BY : SUBHASHINI.B
REG NO: 212223040211

#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int count, min, max;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d ", random_number);
    }
    return 0;
}
```
# OUTPUT
![Screenshot 2024-10-18 135910](https://github.com/user-attachments/assets/f6645da8-d40a-4f61-8bb9-fb0ede0d1cfb)
# RESULT:
 Thus,Program excueted successfully


