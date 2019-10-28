# RunTimePolymorphism



using System;

namespace RunTimePolymorphism

{

    // Base Class

    public class BClass

    {

        public virtual void GetInfo()

        {

            Console.WriteLine("Learn C# Tutorial");

        }

    }

    // Derived Class

    public class DClass : BClass

    {

        public override void GetInfo()

        {

            Console.WriteLine("Learn Polymorphism");

        }

    }

    class Program

    {

        static void Main(string[] args)

        {

            DClass d = new DClass();

            d.GetInfo();

            BClass b = new BClass();

            b.GetInfo();

            Console.WriteLine("\nPress Enter Key to Exit..");

            Console.ReadLine();

        }

    }

}
