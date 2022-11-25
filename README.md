# Square-Pattern-in-Java--Java-Program-





import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
       
        Scanner console = new Scanner(System.in);
        System.out.println("Enter Number of Rows: ");
        int row = console.nextInt();
        for (int i = 1; i<=row; i++ ){
            for (int j =1; j<= row*2; j++){
                System.out.print("*");
            }
            System.out.println();
        }

    }
}
