import java.util.*;
public class countWords {

	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		System.out.print("Enter the string :");		
		String s=sc.nextLine();
		String[] words=s.split(" ");
		System.out.println("The number of words is : "+words.length);
	}

}
