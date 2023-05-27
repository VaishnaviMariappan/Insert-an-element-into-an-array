# EXP7 Write a java program to insert an element into array

## AIM:

To create a java program to insert an element into an array.
## PROCEDURE:

1.Create the class and declare the main method so that the JVM will identify the main program to run.

2.Declare an array and accept the input from user.

3.To accept the inputs from user import Scanner and get the input and store them.

4.Inside for loop use SCANEER to accept the elements of array

5.Print the output using for loop and SYSTEM.OUT.PRINT

6.The program will be executed after the compilation and results are printed.
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
![image](https://github.com/VaishnaviMariappan/Insert-an-element-into-an-array/assets/94169913/82f3b59b-4f35-4262-9cd5-6baed7ce2967)

## RESULT:
Thus a program is created to insert an element into an array.
