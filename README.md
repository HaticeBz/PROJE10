import java.util.Scanner;
public class Main {
        public static void main(String[] args){
                Scanner input = new Scanner(System.in);
                double a, alan, pi = 3.14;
                int r;
                System.out.print("Yarı çapı giriniz :");
                r = input.nextInt();
                System.out.print("Açının derecesini giriniz :");
                a = input.nextDouble();
                alan = (pi * (r * r) * a) / 360 ;
                System.out.print("Alan :" + alan);
        }
}
