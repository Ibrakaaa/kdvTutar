# kdvTutar
Java 101 - KDV Tutarı Hesaplama

import java.util.Scanner;

public class BaslangicTest {
    public static void main(String[] args) {

      double fiyat, kdvOran;

      Scanner input = new Scanner(System.in);

      System.out.print("Lütfen Tutarı Giriniz: ");
      fiyat = input.nextDouble();
      System.out.println("Girmiş Olduğunuz KDV'siz fiyat "+ fiyat+ " TL");

      if(0<fiyat && fiyat <=1000){
        kdvOran=0.18;

      }
      else{
        kdvOran=0.08;
      }

      double kdv = fiyat * kdvOran ;
      System.out.println("Girdiğiniz Fiyatın KDV Tutarı: "+ kdv+ " TL");

      double kdvli = fiyat+kdv;
      System.out.print("KDV'li Toplam Fiyat: "+ kdvli+" TL");




    }
    
    [](www.patika.dev)
    
    
    }
