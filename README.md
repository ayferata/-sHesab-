# -sHesab-
import java.util.Scanner;
public class main {
    static int power(int a, int b) {
        if (a == 1 | b == 0)
            return 1;
        return power(a, b - 1) * a;
    }

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("1 sayi: ");
        int a = input.nextInt();
        System.out.print("2 sayi: ");
        int b = input.nextInt();

        System.out.println("Sonuç: " + power(a, b));
        
    }
}
