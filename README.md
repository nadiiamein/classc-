# classc-
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace klass_Sh
{
    class Worker
    {
        string FIO;
        int DataRozd;
        int Staz;
        int kategoria;
        int oklad;
        public Worker()
        {
             FIO="";
             DataRozd=0;
             Staz=0;
             kategoria=0;
             oklad=0;
        }
        public void Input()
        {
            Console.WriteLine("Enter FIO=");
            FIO = Console.ReadLine();
            Console.WriteLine("Data Birsday=");
            DataRozd = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter staz=");
            Staz = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter kategoria=");
            kategoria = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter oklad=");
            oklad = Convert.ToInt32(Console.ReadLine());
        }
       
        public string Output()
        {
            return "FIO:" + FIO + "Birsday:" + DataRozd.ToString() + "Staz:" + Staz.ToString() + "kategoria:" + kategoria.ToString() + "oklad:" + oklad.ToString();
        }
    
     //Console.ReadKey();

	}
    
}
