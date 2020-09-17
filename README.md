# mini-exam-1


using System;

class MainClass {
  public static void Main (string[] args) {
    Console.WriteLine("enter yourname");
   
    string yourName = Console.ReadLine();
    
    Console.WriteLine("enter height in inches");

    int inches;
    inches = Convert.ToInt32(Console.ReadLine());

    Console.WriteLine("enter weight in pounds");

    int pounds;
    pounds = Convert.ToInt32(Console.ReadLine());

    double BMI;
    BMI = ((703 * pounds)/(inches * inches));
    Console.WriteLine("your BMI is" + BMI);
    if (BMI < 18.5)
    {
      Console.WriteLine("you are underweight");
    }
    if (BMI > 30)
    {
      Console.WriteLine("your are obese");
    }
    if (BMI > 18.5 & BMI < 24.9)
    {
      Console.WriteLine("you are normal");
    }
   if (BMI > 25 & BMI < 29.9)
   {
     Console.WriteLine("you are overweight");
   }




  }
}
