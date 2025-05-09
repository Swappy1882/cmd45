package prac6;
import java.util.Scanner;

import java.util.*;

public class nestedtry {

      public static void main(String[] args)
      {

Scanner sc=new Scanner(System.in);

String[] arr = {"Shahrukh", "Salman", "Amir", "Ajay"};

try

{

System.out.println("Enter the value of input 1"); int

a=sc.nextInt();

System.out.println("Enter the value of input 2"); int

b=sc.nextInt();

int c=a/b;

System.out.println("The result is \t" + c); for(int

i=0;i<=arr.length;i++)

{

System.out.println("Bollywood Heros\t" +arr[i]);

}
}
catch(ArithmeticException e)

{

System.out.println("Divide by zero");
}
catch(InputMismatchException e)

{

System.out.println("Incorrect data type");

}

catch(ArrayIndexOutOfBoundsException e)

{

System.out.println("Uncaught exception");

}

}

}


