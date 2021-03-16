import java.util.Scanner;

public class Calculator 
{
     public static void main(String[] args) 
    {
        Scanner scanner=new  Scanner(System.in);
        while(true)
        {          
        System.out.println("------------WELCOME TO CHAMP CALCI------------- ");
        System.out.println("     C - A- L- C- U - L - A - T - E - R   ");
        System.out.println(" ______________________________");
        System.out.println(" Choose your opttion ");
        System.out.println(" ______________________________");
        System.out.println(" Press 1 for Multiplication   (*)");
        System.out.println(" --------------------------------");
        System.out.println(" Press 2 for Divide           (/)");
        System.out.println(" --------------------------------");
        System.out.println(" Press 4 for Addition         (+)");
        System.out.println(" --------------------------------");
        System.out.println(" Press 5 for Subraction       (-)");
        System.out.println(" --------------------------------");
        System.out.println(" press 6 for cube            (n^3)");
        System.out.println(" --------------------------------");
        System.out.println(" press 7 for Square          (n^2)");
        System.out.println(" --------------------------------");
        System.out.println(" press 8 for Fourth Value    (n^4)");
        System.out.println(" --------------------------------");
        System.out.println(" press 9 for Average  ");
        System.out.println(" --------------------------------");
        System.out.println(" Press 10 for Sum of numbers     ");
        System.out.println(" --------------------------------");
        System.out.println(" Press 11 for Quit     ");
        int option;      
      
       
        option=scanner.nextInt();  

        if(option==1)
        {
            System.out.println("Your Pressed option  - 1  (*)");
            mul();

            
            while(true)
            {
                System.out.println("Do you want to continue with Addition (Y/N)");
                String choice;
                Scanner s=new Scanner(System.in);
                choice=s.next();
                switch(choice)
                {
                    case "y":mul();break;
                    case "n":System.exit(0);break;                    
                }
            }

        }
        else if(option==2)
        {
            System.out.println("Your Pressed option  - 2");
            div();

        }
        else if(option==4)
        {
            System.out.println("Your Pressed option  - 4");
            add();

        }
        else if(option==5)
        {
            System.out.println("Your Pressed option  - 5");
            sub();

        }
        else if(option==6)
        {
            System.out.println("Your Pressed option  - 6");
            cube_value();
        }
        else if(option==7)
        {
            System.out.println("Your Pressed option  - 7");
            square_value();

        }
        else if(option==8)
        {
            System.out.println("Your Pressed option  - 8");
            fourth_value();
        }
        else if(option==9)
        {
            System.out.println("Your Pressed option  - 9");
            average();


        }
        else if(option==10)
        {
            int a=sum_of_numbers();
            System.out.println("Your Pressed option  - 10");
            System.out.println(a);

        }
           else if(option==11)
            {
                System.exit(0);
            }   

      }
    }                           
    public static int mul()
    {
        int result;
        Scanner multiply=new Scanner(System.in);
        System.out.println("Enter the first value : ");
        int first_value=multiply.nextInt();
        System.out.println("Enter the Second value : ");
        int second_value=multiply.nextInt();
        result=first_value*second_value;
        System.out.println(first_value+ " * " + second_value +" = "+result );     
        
        return result;
    }
    public static int div()
    {
        int c;
        Scanner s=new Scanner(System.in);
        System.out.println("Enter the first value : ");
        int first_value=s.nextInt();
        System.out.println("Enter the Second value : ");
        int second_value=s.nextInt();
        c=first_value/second_value;  
        System.out.println(first_value+ " / " + second_value +" = "+c );
        return c;
    }
    public static int add()
    {
        int c;
        Scanner s=new Scanner(System.in);
        System.out.println("Enter the first value : ");
        int first_value=s.nextInt();
        System.out.println("Enter the Second value : ");
        int second_value=s.nextInt();
        c=first_value+second_value;
        System.out.println(first_value+ " + " + second_value +" = "+c );
        
        return c;
    }
    public static int sub()
    {
        int c;
        Scanner s=new Scanner(System.in);
        System.out.println("Enter the first value : ");
        int first_value=s.nextInt();
        System.out.println("Enter the Second value : ");
        int second_value=s.nextInt();
        c=first_value-second_value;
        System.out.println(first_value+ " - " + second_value +" = "+c );
        
        return c;
    }
    public static int cube_value()
    {
        System.out.println("Enter the value :");
        Scanner cube=new Scanner(System.in);
        int d=cube.nextInt();
        int c=d*d*d;
        System.out.println(d+" cube value is =" +c);

        
        return c;
    }
    public static int square_value()
    {
        System.out.println("Enter the value :");
        Scanner cube=new Scanner(System.in);
        int d=cube.nextInt();
        int c=d*d;
        System.out.println(d+" Square  value is =" +c);

        
        return c;
    }
    public static int fourth_value()
    {
        System.out.println("Enter the value :");
        Scanner cube=new Scanner(System.in);
        int d=cube.nextInt();
        int c=d*d*d*d;
        System.out.println(d+" Fourth value is =" +c);

        
        return c;
    }
    public static int average()
    {
        int c;
        Scanner s=new Scanner(System.in);
        System.out.println("Enter the first value : ");
        int first_value=s.nextInt();
        System.out.println("Enter the Second value : ");
        int second_value=s.nextInt();
        c=(first_value+second_value)/2;
        System.out.println("Average of values  = "+c );
        
        return c;
    }
    public static int sum_of_numbers()
    {
        int c;
        Scanner s= new Scanner(System.in);
        int a=0;
        int m=0,num;
        System.out.println("Enter the values :");
        for(int i=0;i<=5;i++)
        {
        num=s.nextInt();
        a+=i;
        }
        System.out.println("Sum of numbers  = "+a);
        
        
        return a;
        
    }
    
}
