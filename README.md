using System;

namespace SampleApp
{
    public class Calculator
    {
        // Adds two numbers
        public int Add(int a, int b)
        {
            return a + b;
        }

        // Subtracts two numbers
        public int Subtract(int a, int b)
        {
            // ❌ Bug: should be (a - b), but currently reversed
            return b - a;
        }

        // Divides two numbers
        public double Divide(int a, int b)
        {
            // ❌ Bug: no check for division by zero testsas
            return a / b;
        }
    }
}
