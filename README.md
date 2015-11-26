# Calculator 





// class Calculator declaration

public class Calculator
{

   private double num1;

   // constractor initialiyzes num1 
   public calculater(double a)
   {

       num1=a;
       
   } // end constractor
   // method to add two numbers  
   public double add(double x){
  
     return num1 += x;
   } //end method add
   //method to subtract 
   public double sub(double x){

     return num1 -= x;
   } //end method sub
   //method to multiply 
   public double mult( double x){

     return num1 *= x;
   }// end method mult
   //method to divide two numbers 
   public double div(double x){

     return num1/=num2;
   }//end method div
   
}// end class Calculator







//class TestCalculator declaration
public class TestCalculator
{
   //main method begins program execution
   public static void main()
   {
     
      Calculater number=new Calculater(9);
      System.out.println(number.add(5));
      System.out,println(number.sub(7));
      System.out.println(number.mult(2));
      System.out.println(number.div(3));
     
    }//end main method
}//end class TestCalculator


 
























  
