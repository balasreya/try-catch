# try-catch
 import java.util.*;
class Main
{
    public static void main(String[]args)
    {
        Scanner s=new Scanner(System.in);
            try {
                int k;
                System.out.println("enter the size of an array");
                k=s.nextInt();
                int a[]=new int[k];
                if(a.length>0)
                {
                   System.out.println("the array size is positive"+a.length);
                }
                else
                {
                     System.out.println("java.lang.negative array size");
                }
            }
            catch(Exception e)
            {
                 System.out.println("e");
            }
    
    }
}
