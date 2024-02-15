# java
java practise exercise codes 
import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
		Scanner scan = new Scanner (System.in);
		System.out.print("Enter Your Number 1 =");
		int num1=scan.nextInt();
			System.out.print("Enter Your Number 2 =");
			int num2=scan.nextInt();
			
				System.out.print("Choose your operation [+, - , * , / ]=");
				char ch = scan.next().charAt(0);
				switch (ch){
				case '+': 	System.out.print("Add = " +(num1+num2));
				          break ;
				case '-': 	System.out.print("Sub = " +(num1-num2));
				          break ;
				case '*': 	System.out.print("Mul = " +(num1*num2));
				          break ;
				case '/' : 	System.out.print("Div = " +(num1/num2));
				          break ;   
				default : System.out.print("You entered wrong option");
				           break ;
				          
				}
	}
}
