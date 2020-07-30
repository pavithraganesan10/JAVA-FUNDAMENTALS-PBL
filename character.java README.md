# JAVA-FUNDAMENTALS-PBL
import java.util.Scanner;
public class character{ 
public static void main(String[] args) { 
Scanner myObj = new Scanner(System.in); 
String value = myObj.nextLine();
char alpha1 =myObj.next().charAt(0); 
char alpha2 = myObj.next().charAt(1);
System.out.printf("%c,%c",alpha1,alpha2);
}
}
