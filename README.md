# Linear-Power

import java.util.*;

public class Main
{
	public static void main(String[] args) {
	
	    Scanner sc = new Scanner(System.in);
	    
	    int x = sc.nextInt();
	    
	    int n = sc.nextInt();
	    
	    int p = power(x, n);
	    
		System.out.println(p);
	}
	
	public static int power(int x, int n){
	    
	    if(n == 1){
	        return x;
	    }
	    if(n == 0){
	        return 1 ;
	    }
	    
	    int po = power(x,n - 1) * x ; 
	    return po;
	}
}


//  /******************************************************************************

                            Online C# Compiler.
			    
                Code, Compile, Run and Debug C# program online.
		
Write your code in this editor and press "Run" button to execute it.


*******************************************************************************/

using System;

class HelloWorld {

  static void Main() {
  
      int x = int.Parse(Console.ReadLine());
      
      int n = int.Parse(Console.ReadLine());
      
       int p = power(x, n);
       
      Console.WriteLine(p);
      
      
    }
    
    static int power(int x, int n){
	    
	    if(n == 1){
	        return x;
	    }
	    if(n == 0){
	        return 1 ;
	    }
	    
	    int po = power(x,n - 1) * x ; 
	    return po;
	}
    
}
    
    
    
    
    
  
