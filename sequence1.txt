import java.util.*;
public class Sequence {
    public static void main(String arg[]){
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the limit: ");
        int limit=sc.nextInt();
        for(int i=2;i<=limit;i=i+2){
            if(i==2)
                System.out.print(i*i);
            else
                System.out.print(","+i*i);
        }
    }
}
