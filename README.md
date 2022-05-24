# Burc-Bulma-Programi

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        int month,day;

        Scanner input = new Scanner(System.in);

        System.out.println("Doğduğunuz Ayı Giriniz :");
        month = input.nextInt();

        System.out.println("Doğduğunuz Günü Giriniz :");
        day = input.nextInt();

        if (month>0 && month<=12) {
            if (month == 1) {
                if (day >0 && day<22) {
                    System.out.println("Oğlak Burcu");
                } else if (day >=22 && day<=31) {
                    System.out.println("Kova Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }
            if (month == 2) {
                if (day >0 && day<20) {
                    System.out.println("Kova Burcu");
                } else if (day >=20 && day<=29) {
                    System.out.println("Balık Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }
            if (month == 3) {
                if (day >0 && day<21) {
                    System.out.println("Balık Burcu");
                } else if (day >=21 && day<=31) {
                    System.out.println("Koç Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }
            if (month == 4) {
                if (day >0 && day<21) {
                    System.out.println("Koç Burcu");
                } else if (day >=21 && day<=30) {
                    System.out.println("Boğa Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }
            if (month == 5) {
                if (day >0 && day<22) {
                    System.out.println("Boğa Burcu");
                } else if (day >=22 && day<=31) {
                    System.out.println("İkizler Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }
            if (month == 6) {
                if (day >0 && day<23) {
                    System.out.println("İkizler Burcu");
                } else if (day >=23 && day<=30) {
                    System.out.println("Yengeç Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }
            if (month == 7) {
                if (day >0 && day<23) {
                    System.out.println("Yengeç Burcu");
                } else if (day >=23 && day<=31) {
                    System.out.println("Aslan Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }
            if (month == 8) {
                if (day >0 && day<23) {
                    System.out.println("Aslan Burcu");
                } else if (day >=23 && day<=31) {
                    System.out.println("Başak Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }
            if (month == 9) {
                if (day >0 && day<23) {
                    System.out.println("Başak Burcu");
                } else if (day >=23 && day<=30) {
                    System.out.println("Terazi Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }
            if (month == 10) {
                if (day >0 && day<23) {
                    System.out.println("Terazi Burcu");
                } else if (day >=23 && day<=31) {
                    System.out.println("Akrep Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }
            if (month == 11) {
                if (day >0 && day<22) {
                    System.out.println("Akrep Burcu");
                } else if (day >=22 && day<=30) {
                    System.out.println("Yay Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }

            if (month == 12) {
                if (day >0 && day<22) {
                    System.out.println("Yay Burcu");
                } else if (day >=22 && day<=31) {
                    System.out.println("Oğlak Burcu");
                }else{
                    System.out.println("Girdiğiniz gün hatalı,lütfen tekrar giriniz");
                }
            }

        }
    }

}
