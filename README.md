# Day9-with-java

It is 3rd day of learning arrays. Today I learned and practiced to write a program that calculates the sum of all elements present in an array.

Here is the program for the above problem:

import java.util.Scanner;
public class ArraySumCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the size of the array: ");
        int size = scanner.nextInt();
        int[] arr = new int[size];
        System.out.println("Enter the array elements:");
        for (int i = 0; i < size; i++) {
            arr[i] = scanner.nextInt();
        }
        int sum = 0;
        for (int i = 0; i < size; i++) {
            sum += arr[i];
        }
        System.out.println("Sum of the array elements: " + sum);
        scanner.close();
    }
}

