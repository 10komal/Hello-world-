# Hello-world
import java.util.Scanner;
public class Main
{
	public static void main(String[] args)
	{
	    Scanner sc= new Scanner(System.in);
	    int a=sc.nextInt();
	    int n=sc.nextInt();
	    do
	    {
	        if(a==0)
	        {
	            break;
	        }
	        if(n>=0 && n<=59)
	        {
	            System.out.println("good As Well");
	            break;
	        }
	        else if(n<=89)
	        {
	            System.out.println("Also Good");
	            break;
	        }
	        else 
	        {
	           System.out.println("Good");
	           break;
	        }
	    }
	    while(a!=0);
	}
}
