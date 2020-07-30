# JAVA-FUNDAMENTALS-PBL
import java.util.Scanner;
public class samelastdigit{ 
public static void main(String[] args) {
Scanner myObj = new Scanner(System.in); 
int number1 = myObj.nextInt(); int number2 = myObj.nextInt(); 
if(number1%10 == number2%10 ) 
System.out.printf("lastDigit(%d,%d) -> true",number1,number2);
else
	System.out.printf("lastDigit(%d,%d) -> false",number1,number2);
}
}
