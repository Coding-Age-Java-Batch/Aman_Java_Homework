//✅ Question 4: 
//Count Even and Odd Numbers
//Problem: Count number of even and odd integers in the array.
//Requirements:
//● Use loop and % operator
//● Maintain counters for both
//Test Scenario:
//Input:{1, 2, 3, 4, 5}→Output:Even = 2, Odd = 3
import java.util.Scanner;
class Even_Odd_Count{

public static void main( String [] args){

    Scanner ui = new Scanner ( System.in );
    
    System.out.print(" Entre size of Array ");
    int size = ui.nextInt();
    
    int [] arr = new int [size];
    System.out.print(" Entre " + size + " Element");
    
    for( int i = 0 ; i < size ; i++ ){
      arr[i] = ui.nextInt();
    }
    
    System.out.print( " Entred Element are ");
    for( int i = 0 ; i < size ; i++ ){
      System.out.print(arr[i] + " , ");
    }
    
    int evenNum = 0 ;
    System.out.println(" \n Even Elements are :  ");
    for( int i = 0 ; i < size ; i ++  ){
        if( arr[i] % 2 == 0 ){
            System.out.print(arr[i] + " ,");
            evenNum ++;
        }
        
    }
    System.out.println(" Number of Even Elements : ");
        System.out.print( evenNum );
        
        int oddNum = 0 ;
    System.out.println(" \n Odd Elements are :  ");
    for( int i = 0 ; i < size ; i ++  ){
        if( arr[i] % 2 != 0 ){
            System.out.print(arr[i] + " ,");
            oddNum ++;
        }
        
    }
    System.out.println(" Number of Odd Elements : ");
        System.out.print( oddNum );
}
}