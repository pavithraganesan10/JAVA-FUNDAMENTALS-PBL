# JAVA-FUNDAMENTALS-PBL
import java.util.Scanner;
public class lowcase{ 
public static void main(String[] args) {
Scanner myObj = new Scanner(System.in);
char ch = myObj.next().charAt(0);
char chLower; 
if(ch>=97 && ch<=122) 
chLower = Character.toUpperCase(ch);
else
	chLower = Character.toLowerCase(ch);
System.out.printf("%c",chLower); 
} 
}
