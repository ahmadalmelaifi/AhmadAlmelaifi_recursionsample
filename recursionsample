/*
*recursionsample
*
*1.0
*
*License type : BSD
*/


public class recursionsample {
	
	//this method would apply the math power
	public static int Power(int base,int exp) {
		if(exp == 0) return 1;
		return base * Power(base,exp-1);
	}
	
	//this method would combine n number this way : (n) + (n - 1) + ...
	public static int Sum(int n) {
		if(n == 0) return n;
		return n + Sum(n-1);
	}
	
	//this method for factorial
	public static int Factorial(int n) {
		if(n == 1) return n;
		return n * Factorial(n-1); 
	}
	
	
	public static void main(String[] args) {
		int n1 = Power(2,3);
		System.out.println(n1);
		
		int n2 = Sum(5);
		System.out.println(n2);
		
		int n3 = Factorial(5);
		System.out.println(n3);
	}
}
