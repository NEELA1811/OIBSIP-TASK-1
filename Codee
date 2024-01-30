import java.util.Scanner;
class Reservation {
public static void main(String[] args) {
    try (Scanner sc = new Scanner(System.in)) {
        System.out.println("-----------------------------WELCOME TO ONLINE RESERVATION SYSTEM--------------------------------");
        String Username = "magic";//stored in database
        String Password = "903";//stored in database
        while(true)
        {
            System.out.println("Enter Username : ");
            String username = sc.next();
            System.out.println("Enter Password : ");
            String password = sc.next();
            if (username.equals(Username) && password.equals(Password)) {
                System.out.println("Access Granted! Welcome!");
                break;
            }
            else if (username.equals(Username)) {
                System.out.println("Invalid Password! Try again..");
                continue;
            }
            else if (password.equals(Password)) {
                System.out.println("Invalid Username!  Try again...");
                continue;
            }
            else {
                System.out.println("Invalid Username & Password!  Try again...");
                continue;
            }
        }
        System.out.println("1.RESERVATION------ 2.CANCELLATION------3.EXIT ");
        System.out.println("Please select any one of the above options");
        int choice=sc.nextInt();
        switch (choice) {
            case 1:
            reservation();
            break;
            case 2:
            cancellation();
            break;
            case 3:{
                System.out.println( "-------------Exit----------");
                System.out.println("Thank You.");
                break;
            }
            default:
            {
                System.out.println("------Invalid choice.Try again------------");
                break;
            }
    }
    }
}
private static void reservation() {
        try (Scanner sc = new Scanner(System.in)) {
            System.out.println("-----------Enter reservation details----------");
            System.out.println("enter passenger name:");
            sc.nextLine();
            System.out.println("enter starting place:");
            sc.nextLine();
            System.out.println("enter destination :");
            sc.nextLine();
            System.out.println("enter date of journey:");
            sc.nextLine();
            System.out.println("enter train number:");
            sc.nextInt();
        }
            System.out.println("----------------------RESERVATION SUCCESSFULL!---------------------------");
            System.out.println("------------------THANK YOU!-----VISIT AGAIN-------------");
    
}
private static void cancellation() {
    try (Scanner sc = new Scanner(System.in)) {
        System.out.println("-----------Enter reservation details----------");
        System.out.println("enter name:");
        sc.nextLine();
        System.out.println("enter train number:");
        sc.nextInt();
        System.out.println("cancel reservation?");
        int con=sc.nextInt();//0-yes 1-no
        if(con==0){
            System.out.println("---------------CANCELLATION SUCCESSFULL---------------");
            System.out.println("----------THANK YOU!-------");
        }
        else
        {
            System.out.println("NOT CANCELLED");
            System.out.println("----------THANK YOU!-------");
        }
    }
    }
}
