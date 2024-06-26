# buatkan-program-untuk-menghitung-luas-dan-keliling-bangun-datar

using System;

class Program {
    static void Main() {
        // Deklarasi variable
        string nama, nim;
        double sisiA, sisiB, tinggi, luas, keliling;
        
        // Input nama dan NIM
        Console.Write("Masukkan nama: NURDIANSYAH PRATAMA ");
        nama = Console.ReadLine();
        Console.Write("Masukkan NIM:1237050130 ");
        nim = Console.ReadLine();

        // Input sisi-sisi trapesium
        Console.Write("Masukkan sisi A: ");
        sisiA = Convert.ToDouble(Console.ReadLine());
        Console.Write("Masukkan sisi B: ");
        sisiB = Convert.ToDouble(Console.ReadLine());
        Console.Write("Masukkan tinggi: ");
        tinggi = Convert.ToDouble(Console.ReadLine());

        // Hitung luas dan keliling
        luas = 0.5 * tinggi * (sisiA + sisiB);
        keliling = sisiA + sisiB + Math.Sqrt(Math.Pow(sisiA, 2) + Math.Pow(tinggi, 2)) + Math.Sqrt(Math.Pow(sisiB, 2) + Math.Pow(tinggi, 2));

        // Output hasil
        Console.WriteLine("Nama:NURDIANSYAH PRATAMA " + nama);
        Console.WriteLine("NIM:1237050139 " + nim);
        Console.WriteLine("Luas trapesium: " + luas);
        Console.WriteLine("Keliling trapesium: " + keliling);
    }
}
