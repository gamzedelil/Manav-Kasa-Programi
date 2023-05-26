# Manav-Kasa-Programi

import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        
        double armut = 2.14, elma = 3.67, domates = 1.11, muz = 0.95,
        patlican = 5.00;
        double kg1,kg2,kg3,kg4,kg5;
        
        
        Scanner input = new Scanner(System.in);
        System.out.println("Aldiginiz urunleri kg olarak yazin.");
       
        System.out.println("Armut:");
        kg1 = input.nextDouble();
        System.out.println("Elma:");
        kg2 = input.nextDouble();
        System.out.println("Domates:");
        kg3 = input.nextDouble();
        System.out.println("Muz:");
        kg4 = input.nextDouble();
        System.out.println("Patlican:");
        kg5 = input.nextDouble();
         
        double toplam = ((kg1*armut) + (kg2*elma) +(kg3*domates) + (kg4*muz)+(kg5*patlican));
       System.out.println("Odenecek tutar:" +toplam);
        toplam = input.nextDouble();
    }
}
