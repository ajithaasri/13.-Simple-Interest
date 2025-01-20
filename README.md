# 13.-Simple-Interest
import java.util.Scanner;

public class SimpleInterest {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter principal amount: ");
        double principal = sc.nextDouble();
        System.out.print("Enter rate of interest: ");
        double rate = sc.nextDouble();
        System.out.print("Enter time (in years): ");
        double time = sc.nextDouble();

        double si = (principal * rate * time) / 100;
        System.out.println("Simple Interest: " + si);
    }
}

Output

Enter principal amount: 1000  
Enter rate of interest: 5  
Enter time (in years): 2  
Simple Interest: 100.0
