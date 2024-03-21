# diffrence of product and sum.java
package demo;

public class diffsumpro {

	public static void main(String[] args) {
		int num=12345;
		int sum=sum(num);
		int product=product(num);
		int result=product-sum;
		System.out.println("The diff between " + product + " and " +sum +" is " +result);
		
	}
	static int sum(int num) {
		int sum=0;
    while(num!=0) {
			sum=sum+num%10;
			num=num/10;
		}
			return sum;
		}
	static int product(int num) {
		int product=1;
		while(num!=0){
		int digit=num%10;
			product=product*digit;
			num=num/10;
			}
			return product;
		}	
	}


			



