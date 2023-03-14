# PrintEvenNumber
print even from 2 to infinte using for and while loop
package mypackage;
import java.util.Scanner;
public class DisplayEvenNumber {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc=new Scanner(System.in);
    int x=sc.nextInt();
    System.out.println("Enter the Number:");
//  for(int i=2;i<=x;i++) {
//	  if(x%2==0) {
//		  System.out.print(x);
//	  }else {
//		  System.out.println();
//	  }
      		while(x<=100) {
    	  if(x%2==0) {
 		  System.out.println(x);
  		  }
                  x++;
                  
    	
    }
    
    		  
    	  }
    	  
      
}
