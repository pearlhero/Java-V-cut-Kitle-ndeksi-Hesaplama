# Java-V-cut-Kitle-ndeksi-Hesaplama
Java-Vücut Kitle İndeksi Hesaplama

import java.util.Scanner;
public class Baslangic {
    public static void main(String[] args) {
        double boy, kilo, vki;


        Scanner inp = new Scanner(System.in);
        System.out.print("Lütfen boyunuzu (metre cinsinde) giriniz : ");
        boy = inp.nextDouble();

        System.out.print("Lütfen kilonuzu giriniz : ");
        kilo = inp.nextDouble();

        vki = kilo / (boy * boy);
        System.out.println("Vücut Kitle İndeksiniz : " + vki);
    }
}
