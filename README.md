# Console.WriteLine("Здраствуйте, введите 2 числа для получения их суммы!");
            int i  = Convert.ToInt32(Console.ReadLine());
            int j = Convert.ToInt32(Console.ReadLine());
            int result = Resh(i, j);
            Console.WriteLine(result);
            int result2 = Resh01(4, 9);
            Console.WriteLine(result2);
            int result01 = Resh01(4,9,7);
            Console.WriteLine(result01);
            int p = 5;
            int g = 8;
            Console.WriteLine(p);
            int result02 = Resh02(g, ref p);
            Console.WriteLine(result02);
            int z = 5;
            int x = 10;
            int y = 2;
            Resh03(x, y, out z);
            Console.WriteLine(z);
            Console.ReadKey();
        }
        static int Resh(int a, int b)
        {
            return a + b;
        }
        static int Resh01(int x, int y, int z = 5)
        {
            return x + y + z;
        }
        static int Resh02(int a, ref int p)
        {
            return p + a;
        }
        static void Resh03(int x, int y, out int z)
        {
            z = (x * x) / y;
        }
