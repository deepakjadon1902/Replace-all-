import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int N = scanner.nextInt();
        scanner.nextLine();
        for (int i = 0; i < N; i++) {
            String line = scanner.nextLine();
            String replacedLine = line.replace("pi", "3.14");
            System.out.println(replacedLine);
        }

        scanner.close();
    }
}
