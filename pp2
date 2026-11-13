
using System;

public class DiscountCalculator
{
    public static double CalculateDiscount(
        double price, double discountPercent)
    {
        double discount = price * discountPercent / 100;
        double finalPrice = price - discount;

        return finalPrice;
    }

    public static void Main()
    {
        double price = 1000;
        double discountPercent = 120;

        double result = CalculateDiscount(price, discountPercent);

        Console.WriteLine("Final Price: " + result);
    }
}
