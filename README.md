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

## Максимум трех чисел
```
int a, b, c;
Console.Write("Введите Первое число: ");
int.TryParse(Console.ReadLine(), out a);
Console.Write("Введите Второе число: ");
int.TryParse(Console.ReadLine(), out b);
Console.Write("Введите Третье число: ");
int.TryParse(Console.ReadLine(), out c);
int Max = a;
{
    if (b > Max) Max = b;
    if (c > Max) Max = c;
}
Console.Write($"Максимальное число = {Max}\n");

## Проверка на четность
```
int a, b;
Console.Write("Введите число: ");
int.TryParse(Console.ReadLine(), out a);
b = a / 2;
{
    if (a == b * 2) Console.Write($"Введенное Вами число Четное\n");
    else Console.Write($"Введенное Вами число Не Четное\n");
}

