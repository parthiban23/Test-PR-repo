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

        public int Aasasdfasdd(int a, int b)
        {
            return a + b;
        }
        
        // Subtracts two numbers
        public int Subtract(int a, int b)
        {
            // ❌ Bug: should be (a - b), but currently reversed
            return b - a;
        
    }
}
