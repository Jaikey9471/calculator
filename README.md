# calculator
culculator using a language of java of method overloading..




import java.util.Scanner;
public class methods_overloding {
    public static void calculator1(int a,int b,String t) {
        if (t.equals("+")) {
            System.out.println(a+b);
        }
        else if (t.equals("-")) {
            System.out.println(a-b);
        }
        else if (t.equals("*")) {
            System.out.println(a*b);
        }
        else if (t.equals("/")) {
            System.out.println(a/b);
            
        }
    }
        public static void main(String args[]){
            Scanner input=new Scanner(System.in);

            System.out.println("Enter a first number=");
            int input1=input.nextInt();

            System.out.println("Enter a second number=");
            int input2=input.nextInt();

            System.out.println("enter a operater(+,-,*,/)=");
            String input3=input.next();

            calculator1(input1,input2,input3);
    input.close();
        }
}

