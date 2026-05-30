using System;

namespace PackageExpress
{
    class Program
    {
        static void Main(string[] args)
        {
            // Print the welcome message
            Console.WriteLine("Welcome to Package Express. Please follow the instructions below.");

            // Prompt the user for the package weight
            Console.Write("Please enter the package weight: ");
            double weight = Convert.ToDouble(Console.ReadLine());

            // Check if the package is too heavy
            if (weight > 50)
            {
                Console.WriteLine("Package too heavy to be shipped via Package Express. Have a good day.");
                return; // End the program
            }

            // Prompt for package dimensions
            Console.Write("Please enter the package width: ");
            double width = Convert.ToDouble(Console.ReadLine());
