# Max.Arr
Finding the Maximum Element in an Array (C Program)
Project Overview
This project demonstrates a simple algorithm to find the maximum element in an array using the C programming language.
It is part of an exercise requiring:
Writing the algorithm
Implementing it in C/C++
 Algorithm
Start by assuming the first element is the maximum.
Loop through the array from index 1 to the last element.
If any element is greater than the current maximum, update the maximum.
After the loop ends, output the maximum value.
C Program Implementation
#include <stdio.h>
int main() {
    int n, i;
    printf("Enter number of elements: ");
    scanf("%d", &n);
   int arr[n];
    printf("Enter %d elements:\n", n);
    for(i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }
 int max = arr[0];
 for(i = 1; i < n; i++) {
        if(arr[i] > max) {
            max = arr[i];
        }
    }
  printf("The maximum element is: %d\n", max);
return 0;
}
Sample Input
Enter number of elements: 5
Enter 5 elements:
10 4 8 15 6
Sample Output
The maximum element is: 15
How to Compile and Run
Compile
gcc max.c -o max

Run
./max

📂 Project Files
max.c
README.md
 Author
James Loka John Dominic
