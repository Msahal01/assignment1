   int product = 1;
        Console.WriteLine("enter a number");
        int number = Convert.ToInt32(Console.ReadLine());

        while (number >= 10)
        {
           
            while (number > 0)
            {
                product *= number % 10;
                number /= 10;
            }
            number = product;
        }

        Console.WriteLine(number);
        Console.ReadKey();