# форматирование текста

## базовые форматы

**жирный текст**  
*курсив*  
***жирный курсив***  
~~зачёркнутый~~  
`код внутри текста`

## блок кода без языка

```
string name;
name = Console.ReadLine();
Console.WriteLine(name);
```

## блок кода c#

```csharp
string name;
name = Console.ReadLine();
Console.WriteLine(name);
```

---

# задание: комментированная программа на c#

## требования

1. имя файла: `FormatDemo.cs`
2. логика:
   - запрашивает два числа
   - выполняет сложение
   - выводит результат

## пример кода

```csharp
Console.WriteLine("Введите первое число: ");
double number1 = Convert.ToDouble(Console.ReadLine());

Console.WriteLine("Введите второе число: ");
double number2 = Convert.ToDouble(Console.ReadLine());

double sum = number1 + number2;
Console.WriteLine($"**Результаты операций: {sum}**");
```