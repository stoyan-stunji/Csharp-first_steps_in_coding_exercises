using System;

namespace _05_Supplies_for_School
{
    internal class Program
    {
        static void Main(string[] args)
        {
            double pricePens = 5.8;
            double priceMarks = 7.2;
            double priceCleaningSoup = 1.2;
            
            int numPens = int.Parse(Console.ReadLine());
            int numMarks = int.Parse(Console.ReadLine());
            int litCleaningSoup = int.Parse(Console.ReadLine());
            int percent = int.Parse(Console.ReadLine());

            double finalPens = pricePens * numPens;
            double finalMarks = priceMarks * numMarks;
            double finalCleaningSoup = priceCleaningSoup * litCleaningSoup;
            double sum = finalPens + finalMarks + finalCleaningSoup;

            double finalPrice = sum - (sum * percent / 100);

            Console.WriteLine(finalPrice);


        }
    }
}
