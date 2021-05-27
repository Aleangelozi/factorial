# factorial
A method to calculate the factorial of a non-negative integer.

Briefly, a factorial of a non-negative integer n, denoted by n!, is expressed by the math expression:
  n! = n(n - 1)(n - 2)(n - 2)∙ ... ∙1. 
  
An extended definition includes:
  1! = 1 and 0! = 1
 
For example,
5! = 5 x 4 x 3 x 2 x 1 = 120.

#Java#

public class Factorial {
	
	public static int calculateFactorial(int n){
		
		for (int i = n; i >= 2 ;){
	        n *= --i;
		}    
		return n;
		
	}
	public static void main(String[] args) {
		System.out.println(calculateFactorial(5));
	}

}


#JavaScript#

function factorial (n) {
  
  for (var i = n; i >= 2 ;){
    n *= --i;
  }  
  return n;
} factorial(5)  
    
