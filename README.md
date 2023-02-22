# -in-Zodya-Hesaplama
www.patika.dev
---------------------


import java.util.Scanner;

public class ÇinZodyağı {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Doğum yılınızı giriniz: ");
        int doğumYılı = scanner.nextInt();

        String[] zodyak = {"Maymun", "Horoz", "Köpek", "Domuz", "Fare", "Öküz", "Tiger", "Tavşan", "Ejderha", "Yılan", "At", "Koyun"};

        System.out.println("Çin Zodyağı burcunuz: " + zodyak[doğumYılı % 12]);
    }
}
