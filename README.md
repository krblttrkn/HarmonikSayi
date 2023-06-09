# HARMONİK SAYI
* java ile girilen sayının harmonik serisini bulan program yazacağız.
```
package DongulerPratik;

import java.util.Scanner;

public class HarmonikSayiHesaplama {
    public static void main(String[] args){
        Scanner inp = new Scanner(System.in);
        System.out.print("N Sayısını Giriniz : ");
        int n=inp.nextInt();
        double result=0;
        for (int i=1;i<=n;i++){
            result+=(1.0/i);
        }
        System.out.print(result);
    }
}
```
# PATİKA PROFİLİM
<a href='https://academy.patika.dev/tr/profile'><u>Patika Profilim</u></a>