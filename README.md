internal class Program
{
    static void Main(string[] args)
    { //gamla kalylaotr
        int num1 = 10;
        int num2 = 3;

        int sum = num1 + num2;
        int diff = num1 - num2;
        int mul = num1 * num2;
        int div = num1 / num2;
        int mod = num1 % num2;

        Console.WriteLine($"Sum: {sum}");
        Console.WriteLine($"Diff: {diff}");
        Console.WriteLine($"Mul: {mul}");
        Console.WriteLine($"Div: {div}");
        Console.WriteLine($"Mod: {mod}");


         if (sum > 10)
        { Console.WriteLine("Stort tal");

        }
        else

        {
            Console.WriteLine("litet tal");

        }
         if (mod == 0)
        {
            Console.WriteLine("Delbart utan rest");
        }
        else
        {
            Console.WriteLine("Har rest");

            Console.ReadKey();
        }
