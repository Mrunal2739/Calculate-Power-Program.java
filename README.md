# Calculate-Power-Program.java

import java.util.*;

class CalculatePower

{

   public static void main(String args[])
   
   { 
   
    
    System.out.println("Enter number");
    
    Scanner sc = new Scanner(System.in);
    
    int num = sc.nextInt();
    
    System.out.println("Enter the power");
    
    int pow = sc.nextInt();
      
    CalculatePower obj = new CalculatePower();
    
    obj.calculatePower(num,pow);
   
   }
   
   void calculatePower(int num, int pow){
     
    int result = 1;
    
     int i = 1;
     
    
    while(i <= pow){
      
      result = result * num;
      
       i++;
    }
     
System.out.println("power of number is = "+result);

}

}
