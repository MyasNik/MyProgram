# MyProgram
package myprogram.pkg1;


public class MyProgram1 {

   
    public static void main(String[] args) {
        int m = 12345; int n =m;
        int s = 0;
        while (n != 0 ){
            s =s + n%10;
            n =n / 10;
        }
        System.out.println("Сумма цифр в числе " + m + " = " + s);
    
        
       
    }
    
}
