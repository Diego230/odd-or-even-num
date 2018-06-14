# odd-or-even-num
i've write this code for know if a number is odd or even, but it doesen't work, plese help me

namespace book_exsersise
{
    class bookexsersise
    {
        static void Main(string[] args)
        
        {
            double reimander, number;
            Console.WriteLine("input the number");
            number = Convert.ToDouble(Console.ReadLine());
            reimander = number%2;
            if (Convert.ToBoolean(reimander = 0))
            {
                Console.WriteLine("the reimander is " + reimander + "so it's a odd number");
            }
            else if (Convert.ToBoolean(reimander = 1))
            {
                Console.WriteLine("the reimander is " + reimander + "so it's a even number");
            }
        } 
    }
}
