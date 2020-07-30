# JAVA-FUNDAMENTALS-PBL
import java.util.Scanner; 
public class evenodd{ 
public static void main(String[] args) { 
Scanner myObj = new Scanner(System.in);
int number1 = myObj.nextInt(); 
if(number1 %2 ==0 ) 
  System.out.printf("Even");
else
	System.out.printf("Odd");
} 
}
