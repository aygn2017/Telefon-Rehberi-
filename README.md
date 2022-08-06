# Telefon-Rehberi-
   static void Main(string[] args)
        {
            directory directory = new directory();

            flag:
            Console.WriteLine("Lütfen yapmak istediğiniz işlemi seçiniz :) ");
            Console.WriteLine("*******************************************");
            Console.WriteLine("(1) Yeni Numara Kaydetmek");
            Console.WriteLine("(2) Varolan Numarayı Silmek");
            Console.WriteLine("(3) Varolan Numarayı Güncelleme");
            Console.WriteLine("(4) Rehberi Listelemek");
            Console.WriteLine("(5) Rehberde Arama Yapmak﻿");

            string choose = Console.ReadLine();

            switch (choose)
            {
                case "1":
                    directory.addNumber();
                    goto flag;
                   // break;
                case "2":
                    directory.deleteNumber();
                    goto flag;
                 //   break;
                case "3":
                    directory.update();
                    goto flag;
                case "4":
                    directory.SortDictionary();
                    goto flag;
                case "5":
                    directory.FindDictionary();
                    goto flag;
                    


            }
            


















        }
    }
}
