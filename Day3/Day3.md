## Problem Statement 
Write a program to find ASCII values of a character

Description:

Get an input character from the user and give the ASCII value of the given input as the output.

Input:

b

Output:

98

Input:

B

Output:

66
## Solution

```java
# Provide your solution here.
import java.util.Scanner;
public class Main{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter a character:");
        char c = sc.next().charAt(0);
        int ASCIIvalue = (int) c;
        System.out.println("The ASCII value of " + c + "  is: " +ASCIIvalue);
    }
}
