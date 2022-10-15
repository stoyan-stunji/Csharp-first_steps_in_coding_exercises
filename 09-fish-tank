using System;

namespace _09_Fish_Tank
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int x = int.Parse(Console.ReadLine());
            int y = int.Parse(Console.ReadLine());
            int z = int.Parse(Console.ReadLine());
            double percent = double.Parse(Console.ReadLine());

            double volCM = x * y * z;
            double volDM = volCM * 0.001;
            double percentReal = 1 - percent / 100;
            double water = volDM * percentReal;

            Console.WriteLine(water);
        }
    }
}
