using System;

namespace _06_Repainting
{
    internal class Program
    {
        static void Main(string[] args)
        {
            double priceForNylon = 1.5;
            double priceForPaint = 14.5;
            double priceForRaz = 5.0;
            double priceForBags = 0.40;

            int numNylon = int.Parse(Console.ReadLine());
            int numPaint = int.Parse(Console.ReadLine());
            int numRaz = int.Parse(Console.ReadLine());
            int hours = int.Parse(Console.ReadLine());

            double sumNylon = (numNylon + 2) * priceForNylon;
            double sumPaint = (numPaint + numPaint * 0.1) * priceForPaint;
            double sumRaz = numRaz * priceForRaz;
            double sumMaterials = sumNylon + sumPaint + sumRaz + priceForBags;
            double sumWorkers = sumMaterials * 0.3 * hours;

            double finalSum = sumWorkers + sumMaterials;

            Console.WriteLine(finalSum);
        }
    }
}
