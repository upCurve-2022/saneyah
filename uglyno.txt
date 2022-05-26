import java.util.*;
public class uglyNumber {

	public static void main(String[] args) {
    System.out.print("Enter the number: ");
    Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		int t=0;
		while(n!=1)
		{
			if(n%5==0)
			{
				n=n/5;
			}
			else if(n%3==0)
			{
				n=n/3;
			}
			else if(n%2==0)
			{
				n=n/2;
			}
			else
			{
				System.out.println("Not an Ugly Number.");
				t=1;
				break;
			}
		}
		if(t==0)
		{
		System.out.println("Ugly Number.");
		}
	}

}
