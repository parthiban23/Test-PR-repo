using System;

namespace SampleApp
{
    class Program
    {
        static void Main(string[] args)
        {
            Calculator calc = new Calculator();

            Console.WriteLine("Sum: " + calc.Add(5, 10));
            Console.WriteLine("Subtract: " + calc.Subtract(5, 10)); // Should be -5, but bugged
            Console.WriteLine("Divide: " + calc.Divide(10, 0)); // ❌ Runtime crash here
        }
    }
}
