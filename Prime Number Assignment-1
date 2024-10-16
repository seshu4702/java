import java.io.*;
import java.util.*;
class Main
{
    public static void main(String args[])
    {
        int first;
        int second;
        boolean response;
   
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the starting value: ");
        first = sc.nextInt();
     System.out.println("Enter the ending value: ");
        second = sc.nextInt();
        sc.close();
   
        if (first < 2)
            first = 2;
        if (second < 2)
        {
        System.out.println("No prime numbers in range.");
        return;
        }
   
        System.out.println("Result: ");
        for(int i = first; i <= second; i++)
        {
        response = false;
            for(int j = 2; j < i; j++)
            {
                if(i % j == 0)
                {
                response = true;
                }
            }
            if(!response)
                System.out.println(i);
        }    
    }
}
