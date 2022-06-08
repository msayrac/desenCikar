# desenCikar
import java.util.Scanner;

public class Main {
    static int desenCikar(int n){
        int tempN=n;
        do{
            tempN=tempN-5;
            System.out.println(tempN);
        }while(tempN!=0 && tempN>0);
        do{
            tempN=tempN+5;
            System.out.println(tempN);
        } while(tempN!=n);
        return 0;
   }
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("Enter a number : ");
        int n= input.nextInt();
        desenCikar(n);
    }
}
