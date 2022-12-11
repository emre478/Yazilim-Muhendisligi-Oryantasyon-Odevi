Ad Soyad : Emre Özer
Öğrenci Numarası : 225541029  
Video Linki : https://www.youtube.com/watch?v=hT2vLTIFXOQ

public class Main {

    public static void main(String[] args) {
        System.out.println("Hello world!");
    }
}

public class SayiToplama {

    public static void main(String[] args ) {

        int a = 8;
        int b = 10;
        int c = a + b;

        System.out.println("c =" + c);

    }
}

public class SayiToplama2 {

    public static void main(String[] args){

        double a = 10.5;
        double b = 82.65;

        double c = a + b;

        System.out.println("c="+c );

    }
}

public class OndalikSayi {
    public static void main(String[] args) {

        float a = 3.2f;
        float b= 8.6f;

        float carpim = a * b;

        System.out.println("Çarpım Sonucu: " + carpim);

    }

}

import java.util.Scanner;

public class KalanHesapla {
    public static void main(String[] args) {

        int bolunen = 25, bolen = 4;

        int bolum = bolunen / bolen;
        int kalan = bolunen % bolen;

        System.out.println("Bölüm = " + bolum);
        System.out.println("Kalan = " + kalan);

    }
}

import java.util.Scanner;

public class OrtalamaHesapla {
    public static void main(String[]args) {

    Scanner input = new Scanner(System.in);

    System.out.print("Iki sayi giriniz:");
     double sayi1 = input.nextDouble();
     double sayi2 = input.nextDouble();

    double ortalama =  (sayi1 + sayi2) /2;

    System.out.println(sayi1+""+ sayi2 + "" + "Ortalaması:"+ ortalama );

    }

}

import java.util.Scanner;

public class AlanHesapla {
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);

        System.out.print("Lütfen capi giriniz:");
        int cap = input.nextInt();
        if (cap<0){
            System.out.println("Yanlış giriş ");
        }
    else {
            double alan = cap * cap * 3.14;
            System.out.println("Alan:" + alan );
        }

    }
}

public class SayiSirala {

    public static void main(String[] args) {
        double a = -5, b = 11.4, c = 5;

        System.out.println(a);
        System.out.println(b);
        System.out.println(c);
        System.out.println("");
        if( a >= b && a >= c)
            System.out.println(a + " sayısı büyüktür.");
        else if (b >= a && b >= c)
            System.out.println(b + " sayısı büyüktür.");
        else
            System.out.println(c + " sayısı büyüktür.");
    }
}

import java.util.Scanner;

public class PozitifNegatif {

    public static void main(String[] args) {
        Scanner reader = new Scanner(System.in);
        System.out.print("Bir Sayı Girin:");

        double sayi = reader.nextInt();

        if (sayi < 0.0)
            System.out.println(sayi + " Negatiftir.");

        else if ( sayi > 0.0)
            System.out.println(sayi + " Pozitiftir.");

        else
            System.out.println(sayi + "  Sıfırdır.");
    }
}

import java.util.Scanner;
public class ArdisikSayiToplama {
    public static void main(String[] args) {
        int sayi = 20, toplam = 0;

        for(int i = 1; i <= sayi; ++i)

            toplam += i;
        System.out.println("Toplam = " + toplam);
    }

}
