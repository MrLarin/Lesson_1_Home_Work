# Lesson_1_Home_Work
## Максимум двух чисел
```
int a, b;
Console.Write("Введите Первое число: ");
int.TryParse(Console.ReadLine(), out a);
Console.Write("Введите Второе число: ");
int.TryParse(Console.ReadLine(), out b);
int Max = a;
{
    if (b > Max) Max = b;
}
Console.Write($"Максимальное число = {Max}\n");
```

