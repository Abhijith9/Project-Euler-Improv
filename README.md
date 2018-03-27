# Project-Euler-Improv
This is my attempt at solving problems from Project Euler.Anyone is welcome to view or improve my way of solving them.Cheers!  

//Language Used : Java

/*
  If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23. 
  Find the sum of all the multiples of 3 or 5 below 1000.
*/

public class MyClass {
    public static void main(String args[]) {
       int number = 1;
       int result = 0;
       
       while(number < 1000) {
           if(number % 3 == 0 || number % 5 == 0) {
               result = result + number;
               
           }
           number++;
       }
       System.out.println("sum of all the multiples of 3 or 5 below 1000 : " + result);
    }
}
//Answer : 233168
