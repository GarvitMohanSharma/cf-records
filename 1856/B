import java.util.Scanner;

public class alpha {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int t = scanner.nextInt();

        while (t-- > 0) {
            int n = scanner.nextInt();
            long cs = 0;

            for (int p = 0; p < n; p++) {
                int x = scanner.nextInt();
                if (x == 1) {
                    cs--;
                } else {
                    cs += (x - 1);
                }
            }

            if (n > 1 && cs >= 0) {
                System.out.println("YES");
            } else {
                System.out.println("NO");
            }
        }

        scanner.close();
    }
}
