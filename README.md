# StringReversal

import java.util.Scanner;
class reversal {
    public static void main(String[] args) {
        String original, reverse = "";
        Scanner in = new Scanner(System.in);
        System.out.println("Enter the string");
        original = in.nextLine();

        int length = original.length();
       // System.out.println(length);

        for(int i = length - 1; i >= 0; --i) {
            reverse = reverse + original.charAt(i);
        }
            System.out.println("Reverse of string is :" + reverse);
        }

    }
