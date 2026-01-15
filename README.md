# PF---Assignment
Qno. 6


// Online Java Compiler
// Use this editor to write, compile and run your Java code online

   import java.util.Scanner;

public class TrapezoidArea {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        // Fixed values
        double a = 10;
        double b = 14;
        double h = 6;

        double area = h * (a + b) / 2;

        System.out.println("Side a = " + a);
        System.out.println("Side b = " + b);
        System.out.println("Height = " + h);
        System.out.println("Area of Trapezoid = " + area);

        sc.close();
    }
}
