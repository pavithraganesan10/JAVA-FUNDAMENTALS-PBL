# JAVA-FUNDAMENTALS-PBL
import java.util.Scanner; 
public class percentage{ 
public static void main(String[] args) { 
Scanner myObj = new Scanner(System.in);
String string1 = myObj.nextLine(); 
int age = myObj.nextInt(); 
if(string1.equals("Female")){ 
if( age>=1 && age<=58) 
System.out.println("the percentage of interest is 8.2%"); 
else
System.out.println("the percentage of interest is 9.2%"); 
}
else {
if( age>=1 && age<=58)
System.out.println("the percentage of interest is 8.4%");
else
System.out.println("the percentage of interest is 10.5%"); 
}
}
}
