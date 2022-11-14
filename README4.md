## Temel Kavramlar ve Değişkenler (Not Ortalaması Hesaplama)

```
import java.util.Scanner;
public class Main {
	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		
		System.out.println(" Matematik notunu giriniz");
		
		int a = input.nextInt();
		
		System.out.println("Fizik  notunu giriniz");
		
		int b = input.nextInt();
		
		System.out.println("Kimya notunu giriniz:  ");
		int c = input.nextInt();
		
		System.out.println("Turkce notunu giriniz:  ");
		int d = input.nextInt();
		
		System.out.println("Tarih  notunu giriniz:  ");
		int e = input.nextInt();
		
		System.out.println("Muzik notunu giriniz:  ");
		int f = input.nextInt();
		
		int g = a + b + c + d + e + f;
		int ortalama = g / 6;
		System.out.println("Not ortalamasi:  " + ortalama);
		
	}
}
```
