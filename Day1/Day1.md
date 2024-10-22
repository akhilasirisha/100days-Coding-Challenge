## Problem Statement 
Write a program to identify if the character is a vowel or consonant.

Description of the program: 


Take an input character from the user and check whether the given input is a vowel or consonant.

Input

A

Output

Vowel

Input

m

Output

Consonant

Input

3

Output

Invalid Input

 
## Solution

```java
# Provide your solution here.

import java.util.Scanner;
public class Main{
public static void main (String args[]){
    Scanner sc = new Scanner(System.in);
    char c = sc.next().charAt(0);
    System.out.println(" Enter a character:");
    if( c == 'A'|| c == 'E' || c == 'I' || c == 'O'|| c == 'U'|| c =='a'|| c == 'e' || c == 'i' || c == 'o'|| c == 'u')
    {
    System.out.println("Vowels");
    }
     else if((c>='A' && c<='Z')|| (c>='a' && c<='z'))
    {
    System.out.println("Consonants");
    }
    else
    {
    System.out.println("invalid");
    }

     }
}
