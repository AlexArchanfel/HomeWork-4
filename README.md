// Задача 4. Напишите программу, которая принимает на вход три числа и выдаёт максимальное из этих чисел/

Console.WriteLine("Первое число "); 
int x = int.Parse(Console.ReadLine()!);
Console.WriteLine("Второе число "); 
int y = int.Parse(Console.ReadLine()!);
Console.WriteLine("Третье число "); 
int z = int.Parse(Console.ReadLine()!);
if (x > y && x > z)
{
    Console.WriteLine($"Самое большое число {x}");
}
else if(y > x && y > z)
{
    Console.WriteLine($"Самое большое число {y}");
}
else 
{
    Console.WriteLine($"Самое большое число {z}");
}
