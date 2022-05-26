import java.util.*;
import java.lang.Math;
public class BinToDec {
    public static void main(String arg[]){
        double decimalNum=0;
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter a binary number: ");
        int binaryNum=sc.nextInt();
        int i=0;
        while(binaryNum>0){
            int temp=binaryNum%10;
            decimalNum=decimalNum+(temp*Math.pow(2,i));
            i++;
            binaryNum=binaryNum/10;
        }
        System.out.print("Decimal number: "+decimalNum);
    }
}
