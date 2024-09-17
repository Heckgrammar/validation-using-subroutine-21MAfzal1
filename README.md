        {
            Console.WriteLine("Enter first name");
            string firstName = Console.ReadLine();
            Console.WriteLine("Enter last name");  
            string lastName = Console.ReadLine();
            Console.WriteLine("Enter age");
            int age = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter your password");
            string password = Console.ReadLine();
            Console.WriteLine("Enter email address");
            string emailAddress = Console.ReadLine();




            string username = (firstName + lastName + age);
            Console.WriteLine("Username is " + username + " you have successfully registered please remember your password");
        }
    }
} temporary 
