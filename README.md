# Day9-with-java

It is 3rd day of learning arrays. Today I learned and practiced to write a program that calculates the sum of all elements present in an array.

Here is the program for the above problem:

import java.util.Scanner;

public class ArraySumCalculator {

    public static void main(String[] args) {
    
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the size of the array: "); // It takes the size of array Ex: 4
        int size = scanner.nextInt(); //Scans the size of an array
        int[] arr = new int[size];
        System.out.println("Enter the array elements:"); //Takes elements of array Ex: 1, 2, 3, 5
        
        for (int i = 0; i < size; i++) { //condition for the range of array elements
            arr[i] = scanner.nextInt();
        }
        
        int sum = 0;
        for (int i = 0; i < size; i++) { //condition for sum of array elements 
            sum += arr[i]; // adds all elements in array Ex: 1+2+3+5
        }
        
        System.out.println("Sum of the array elements: " + sum); // Ex: 10
        scanner.close();
    }
}

sample output : Enter the size of the array: 4

Enter the array elements: 1 2 3 5

Sum of the array elements: 10




