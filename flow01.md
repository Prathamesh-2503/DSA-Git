# Practice-Git

1.Input a year and find whether it is a leap year or not.
   public class flow01 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter year :");
        int year = sc.nextInt();
        if((year % 4 == 0 && year % 100 != 0) || (year % 400 ==0)){
            System.out.println(year + " is a leap year");
        }else{
            System.out.println(year + " is not a leap year");
        }
    }
   }


2.Take two numbers and print the sum of both.
    public class flow01 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter first num");
        int a = sc.nextInt();
        System.out.println("Enter second num");
        int b = sc.nextInt();
        int sum = a+b;
        System.out.println(sum);
    }
}


3.Take a number as input and print the multiplication table for it.
    public class flow01 {
      public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter a num :");
        int num = sc.nextInt();
        for(int i =1; i<=10; i++){
            System.out.println(num*i);
        }
      }
    }


4.Keep taking numbers as inputs till the user enters ‘x’, after that print sum of all.

