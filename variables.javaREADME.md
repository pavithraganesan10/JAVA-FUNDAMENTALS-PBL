# JAVA-FUNDAMENTALS-PBL
import java.util.Scanner; 
public class variable{ 
public static void main(String[] args) { 
Scanner myObj = new Scanner(System.in); 
char alpha =myObj.next().charAt(0); 
if((alpha>=65 && alpha<=90) ||( alpha>=97 && alpha<=122))
System.out.println("Alphabet");
else if(alpha >=48 && alpha<=57)
System.out.println("Digit"); 
else
System.out.println("Special Character");
}
}
