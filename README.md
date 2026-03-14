package JavaAssesment;

public class Java {
    public static void main(String[] args) {

        int n = 5;
        for (int row = 0; row < n; row++) {
            for (int space = 0; space < n - row - 1; space++) {
                System.out.print(" ");
            }
            for (int col = 0; col < (2 * row + 1); col++) {

                if (col == 0 || col == (2 * row)) {
                    System.out.print("*");
                } else {
                    System.out.print(" ");
                }

            }
            System.out.println();
        }

        for (int row = n - 2; row >= 0; row--) {

            for (int space = 0; space < n - row - 1; space++) {
                System.out.print(" ");
            }
            for (int col = 0; col < (2 * row + 1); col++) {

                if (col == 0 || col == (2 * row)) {
                    System.out.print("*");
                } else {
                    System.out.print(" ");
                }

            }
            System.out.println();
        }
    }
}
