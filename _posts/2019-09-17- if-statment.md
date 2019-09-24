namespace if_statement
{
    class Program
    {
        static void Main(string[] args)
        {
            string temp; // used to store strings until they are converted

            // get the numbers from the user
            Console.WriteLine("Enter number A:");
            int a = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter number B:");
            int b = Convert.ToInt32(Console.ReadLine());

            if (a > b)
            {
                Console.WriteLine("A is biggest");
                Console.ReadLine();
            }
            else
            {
                Console.WriteLine("B is biggest");
                Console.ReadLine();
            }
        }    
    }
}
