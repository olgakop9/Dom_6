# void PositiveNumbers()
{
    Console.Write("Количество чисел: ");
    int size = Convert.ToInt32(Console.ReadLine());
    int count = 0;
    for (int i = 0; i < size; i++)
    {
        Console.Write($"Введите число номер {i + 1} - ");
        int num = Convert.ToInt32(Console.ReadLine());
        if (num > 0)
            count++;
    }
    Console.WriteLine($"Вы ввели {count} положительных числа");
}
PositiveNumbers();
