using System;


class Program


{
    static void Main()
    {
        int price;
        string productName;
        
        Console.Write("Enter a name of product:");
        productName = Console.ReadLine();
        
        Console.Write("Enter a price of product:");
        price = int.Parse(Console.ReadLine());
        
        Console.WriteLine("Your products:");
        Console.WriteLine("Name: " + productName);
        Console.WriteLine("Price: " + price)
    }
}