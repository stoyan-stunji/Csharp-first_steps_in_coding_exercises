using System;

namespace _03_Deposit_Calculator
{
    internal class Program
    {
        static void Main(string[] args)
        {
            double deposit = double.Parse(Console.ReadLine());
            int time = int.Parse(Console.ReadLine());
            double percent = double.Parse(Console.ReadLine());

            double lihva = deposit * percent / 100;
            double lihvaEdin = lihva / 12;
            double sum = deposit + time * lihvaEdin;

            Console.WriteLine(sum);
        }
    }
}
