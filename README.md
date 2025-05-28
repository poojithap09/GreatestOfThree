# GreatestOfThree
Create a Java program to find the greatest of three numbers using the ternary operator. The program should take three integer inputs and determine the largest number among them using a nested ternary operator.  Input Format  The input consists of three space-separated integers, a, b, and c. 


import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
       Scanner ob=new Scanner(System.in);
        int a = ob.nextInt();
        int b = ob.nextInt();
        int c = ob.nextInt();
        int larg1 = ( a > b ) ? a : b ;
         int larg2 = (larg1 > c ) ? larg1 : c;            
        System.out.println(larg2 );
 
    }
}
