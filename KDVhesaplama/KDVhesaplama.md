import java.util.Scanner;

public class kdvTutarHesaplama {
public static void main(String[] args) {
        
Scanner inp = new Scanner(System.in);

double tutar,kdvoran = 0.18,kdvtutar,kdvlitutar;
 System.out.print("ücret Tutarını Girin :");
 tutar = inp.nextDouble();

kdvtutar = tutar * kdvoran;
kdvlitutar = tutar + kdvtutar;

 System.out.println("KDVORANI :"
 + kdvoran);
System.out.println("KDVSİZ FİYAT :" + tutar);
 System.out.println("KDV TUTARI :" + kdvtutar);
System.out.print("KDVLİ Tutar :" + kdvlitutar);


    }

[PAtika](https://www.patika.dev)
