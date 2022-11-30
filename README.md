# Ogrenci-S-nav-Not-Ortalamas-Gosteren-Uygulama
C# diliyle Ogrenci Sınav Not Ortalaması Gosteren Uygulama projesi - Turkcell


https://gelecegiyazanlar.turkcell.com.tr/konu/egitim/c-ile-algoritma-ve-programlama-101/ogrenci-sinav-not-uygulamasi



using System;

namespace MyApp // Note: actual namespace depends on the project name.
{
    internal class Program
    {
        static void Main(string[] args)
        {
            
            String ad, soyad, bolum, ders;
            int s1, s2, s3, ort;

            ad= "Berat";
            soyad= "Gunaydın";
            bolum= "Elektrik";
            ders= "algoritma";

            s1= 65;
            s2= 75;
            s3= 88;
            ort= (s1 + s2 + s3) / 3;

            Console.WriteLine("***** Ogrenci Bilgi Sistemi *****");

            Console.WriteLine();
            Console.WriteLine("Ogrenci Adı Soyadı:" + ad + " " + soyad);
            Console.WriteLine("Bölüm: " + bolum );
            Console.WriteLine("Ders: " + ders);
            Console.WriteLine();
            Console.WriteLine("sınav 1: " + s1 );
            Console.WriteLine("sınav 2: " + s2 );
            Console.WriteLine("sınav 3: " + s3 );
            Console.WriteLine("Ortalamanız:"+ ort);

            Console.WriteLine("***** Ogrenci Bilgi Sistemi *****");

            Console.Read();





        }
    }
}
