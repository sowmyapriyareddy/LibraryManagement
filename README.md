# LibraryManagement
import java.util.Scanner;

public class Calcul {

	public static void main(String[] args) {
	int a,b;
	
	Scanner sc = new Scanner(System.in);
	try {
	System.out.println("enter the first number:");
	a=sc.nextInt();
	System.out.println("enter second number:");
	b=sc.nextInt();
	System.out.println("add of two numbers="+(a+b));
	System.out.println("sub of two numbers="+(a-b));
	System.out.println("mul of two numbers="+(a*b));
	System.out.println("div of two numbers="+(a/b));

	}
	catch(Exception e) {
		System.out.println("invalid input");
	}
	}
}
