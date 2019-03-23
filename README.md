# Speed

import java.util.Scanner;

public class P23_Speed {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        double num = Integer.parseInt(scanner.nextLine());


        if ( num <= 10.0) {
            System.out.println("slow");
        }
        else if ( num < 50.0 ) {
            System.out.println("average");
        }
        else if ( num < 150.0 ) {
            System.out.println("fast");
        }
        else if ( num < 1000.0 ) {
            System.out.println("ultra fast");
        }
        else if ( num > 1500.0 ) {
            System.out.println("extremely fast");
        }



    }
}
