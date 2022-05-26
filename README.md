using System;

namespace bogdanov
{
class Program
{
public static void Main(string[] args)
{
string uch = "Ученики"+ "[";


Console.Write("Укажите код_номер ученика = ");
int nomer = Convert.ToInt32(Console.ReadLine());

string rom =  uch + nomer + "]";

Console.Write(rom + ".ДАТА РОЖДЕНИЯ. ДЕНЬ = ");
int day = Convert.ToInt32(Console.ReadLine());

Console.Write(rom + ".ДАТА РОЖДЕНИЯ. МЕСЯЦ = ");
int month = Convert.ToInt32(Console.ReadLine());

Console.Write(rom + ".ДАТА РОЖДЕНИЯ. ГОД = ");
int year = Convert.ToInt32(Console.ReadLine());

Console.Write(rom + "КЛАСС. = ");
int klass = Convert.ToInt32(Console.ReadLine());


}

public static void Bag(string[] args){
Console.ReadKey(true);
}
}
}
