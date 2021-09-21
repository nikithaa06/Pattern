# Pattern
import java.util.Scanner;
public class Sample {
    public static void main(String args[])
    {
        int i,j;
        for(i=0;i<5;i++)
        {
            for(j=0;j<=i;)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
