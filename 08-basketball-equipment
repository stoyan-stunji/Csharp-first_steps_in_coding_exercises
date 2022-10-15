using System;

namespace _08_Basketball_Equipment
{
    internal class Program
    {
        static void Main(string[] args)
        {
            double yearPayment = double.Parse(Console.ReadLine());

            double priceShoes = yearPayment - (yearPayment * 0.4);
            double priceClothes = priceShoes - (priceShoes * 0.2);
            double priceBall = priceClothes / 4;
            double priceAcc = priceBall / 5;

            double priceAll = yearPayment + priceShoes + priceClothes + priceBall + priceAcc;

            Console.WriteLine(priceAll);
        }
    }
}
