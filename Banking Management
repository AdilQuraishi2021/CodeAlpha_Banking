import java.util.Scanner;

class Banking{
    public static double balance = 10000;
    public static void deposit(double money){
        if(money > 0){
            balance += money;
            System.out.println("Amount of "+money+" deposited Successfully");
        }
        else
            System.out.println("Negative amount of money can not be deposit");
        System.out.println();
        System.out.println();
    }

    public static void withdraw(double money){
        if(money < balance){
            balance -= money;
            System.out.println("Amount of "+money+" withdraw from your account");
        }
        else
            System.out.println("Insuffucient account balance");
        System.out.println();
        System.out.println();
    }

    public static void checkBalance(){
        System.out.println("Your current balance : "+balance);
        System.out.println();
        System.out.println();
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        boolean flag = true;
        while (flag) {
            int wish = -1;
            System.out.println("Press   1   for deposit ");
            System.out.println("Press   2   for Withdraw ");
            System.out.println("Press   3   to check balance ");
            System.out.println("Press   4   to exit the program ");
            System.out.println("Please Enter your choice ");
            wish = sc.nextInt();
            switch (wish) {
                case 1:
                    System.out.println("Enter amount, you want to deposit ");
                    double money = sc.nextDouble();
                    deposit(money);
                    break;
                case 2:
                    System.out.println("Enter amount, you want to deposit ");
                    money = sc.nextDouble();
                    withdraw(money);
                    break;
                case 3:
                    checkBalance();
                    break;
                case -1:
                    flag = false;
                    break;
                default:
                    break;
            }
        }
        }
}
