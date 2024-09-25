# com413week1

import java.util.Scanner;
public class task1 {
    public static  void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter initial");
        String initial = scanner.nextLine();

        System.out.println("Enter  surname");
        String Surname = scanner.nextLine();

        System.out.println("Enter  age ");
        int age = scanner.nextInt();

        System.out.println("are you currently employed yes or no :");
        String IsEmployed = scanner.nextLine();


        If ( IsEmployed = "Yes")
        System.out.println(initial + Surname + "is currently employed");
        else
        System.out.println("Invalid Input");






    }
}






