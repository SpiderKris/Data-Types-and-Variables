# Data-Types-and-Variables
Data Types and Variables
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _19012017
{
    internal class Program
    {
        private static void Main(string[] args)
        {
            double width = double.Parse(Console.ReadLine());
            double height = double.Parse(Console.ReadLine());
            var perimeter = 2*(width + height);
            var area = width*height;
            var diagonal = Math.Sqrt((width*width) + (height + height));
            Console.WriteLine( perimeter );
            Console.WriteLine( area );
            Console.WriteLine( diagonal );

        }
    }
}
