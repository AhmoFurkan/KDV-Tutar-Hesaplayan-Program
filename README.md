# KDV-Tutar-Hesaplayan-Program
Eğer girilen tutar 0 ve 1000 TL arasında ise KDV oranı %18 , tutar 1000 TL'den büyük ise KDV oranını %8 olarak KDV tutarı hesaplayan programı yazınız.

import  java.util.Scanner;

public class Main {
    public static void main(String[] args) {


       double   tutar,kdvOran=0.18, kdvTutar, kdvliTutar;
       Scanner inputtt = new Scanner(System.in);
       System.out.print("Ücret Tutarını Giriniz :");
       tutar = inputtt.nextInt();

       kdvTutar =tutar * kdvOran;
       kdvliTutar = tutar +kdvTutar;

       System.out.println("KDV'siz Tutar :" + tutar);
       System.out.println("KDV Oranı :" + kdvOran);
       System.out.println("KDV Tutarı :" + kdvTutar);
       System.out.println("KDV'li Tutarı :" + kdvliTutar );
       System.out.println(kdvliTutar);
         }
       }  
