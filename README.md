# Inserting-element-into-an-Array

## AIM:

To write the java program to insert an element into array.

 ## ALGORITHM:
 
 ### Step 1:
 Create the class and declare the main method so that the JVM will identify the main program to run.
 
 ### Step 2:
 Declare an array and accept the input from user.
 
 ### Step 3:
 To accept the inputs from user import Scanner and get the input and store them.
 
 ### Step 4:
 Inside for loop use SCANEER to accept the elements of array
 
 ### Step 5:
 Print the output using for loop and SYSTEM.OUT.PRINT
 
 ### Step 6:
 The program will be executed after the compilation and results are printed.
 
 ## PROGRAM:
 
 ```java
 import java.util.Scanner;
public class Array {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int n= sc.nextInt();
        int[] arr =new int[n];
        for(int i=0;i<n;i++){
            arr[i]=sc.nextInt();
        }
        System.out.print("Array elements are: ");
        for(int i=0;i<n;i++){
            System.out.print(arr[i]+" ");
        }
    }
}
 ```
 
 ## OUTPUT:
 ![image](https://github.com/Aashima02/Insert-element-into-array/assets/93427086/7fee3f7d-7faa-4bc6-a580-47dc97383d66)

 
 ## RESULT:
 Thus The Program is complied successfully.
