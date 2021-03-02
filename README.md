using System;

namespace City
{
    class Building
    {
        private int floors { get; set; }
        private string adress { get; set; }

        public Building(int floors, string adress)
        {
            this.floors = floors;
            this.adress = adress;
        }

    }   

    class Car
    {
        private string brand { get; set; }
        private string colour{ get; set; }
        
        public Car(string brand, string colour)
        {
            this.brand = brand;
            this.colour = colour;
        }
    }

    class Street
    {
        private string name { get; set; }

        public Street(string name)
        {
            this.name = name;
        }
    }

    class Client
    {
        static void Main(string[] args)
        {
            Building b = new Building (5, "Armoniei");
            Car c = new Car ("Toyota" , "Red");
            Street s = new Street ("Armoniei");
            
        }
    }
}
