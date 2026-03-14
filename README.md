# java-test-0003-final-12172-punam
Final Project Assignment - This repository contains the complete final project code and documentation.
public class AlternatingTriangle {
    public static void main(String[] args) {
        int rows = 6;

        for (int i = 1; i <= rows; i++) {

            int num;
            if (i % 2 == 1) {
                num = 1;
            } else {
                num = 0;
            }

            for (int j = 1; j <= i; j++) {
                System.out.print(num);

                if (num == 1) {
                    num = 0;
                } else {
                    num = 1;
                }
            }

            System.out.println();
        }
    }
}
