Вы задаете пользователю ряд вопросов, таких как "Как ваше имя?", "Сколько вам лет?", "Какой ваш знак зодиака?" и т.п. Пользователь отвечает на эти вопросы. Затем, на основе полученной информации, вы составляете краткое описание пользователя.
Пример описания:
"Ваше имя Алексей, вам 21 год, вы по знаку зодиака Водолей и работаете на заводе."


using System;

namespace Lesson1
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Как вас зовут?");
            string firstName = Console.ReadLine();

            Console.WriteLine("Сколько вам лет?");
            int age = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Какой ваш знак зодиака?");
            string zodiacSign = Console.ReadLine();

            Console.WriteLine("Ваша проффесия?");
            string jobs = Console.ReadLine();

            Console.WriteLine("Вас зовут {0}, ваш возраст {1}, вы {2}, ваша проффесия {3}.", firstName, age, zodiacSign, jobs);
        }
    }
}
