## Problem Statement 
Write a program to identify if the character is an alphabet or not.

Description:

Take an input character from user and check whether it is an alphabet or not.

Input :

A

Output: 

Alphabet

Input:

7

Output:

Not an alphabet

## Solution

```java
# Provide your solution here.
import java.util.Scanner;
    public class Main{
        public static void main(String args[]){
            Scanner sc = new Scanner(System.in);
            char c = sc.next().charAt(0);
            System.out.println("Enter a character");
            if((c == 'A' &&  c <='Z' )|| (c == 'a' &&  c <='z'))
             System.out.println("Alphabet");
            else if((c>=0))
            System.out.println("Not alphabet");
            else
            System.out.println("Invalid Input");
        }
}
