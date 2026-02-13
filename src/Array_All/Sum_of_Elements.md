//
//✅
//  Question 1: Sum of Array Elements

//   Problem: Calculate the sum of all elements in an integer array.
//
//   Requirements:
//        ● Accept or define an integer array
//        ● Use loop to calculate the total
//        ● Return or print the sum

// Test Scenario:
// Input: {1, 2, 3, 4} → Output: 10


import java.util.Scanner;

public class Sum_of_Elements {
public  static void main(String[] args) {

      Scanner ui = new Scanner( System.in);

      System.out.print(" Enter Size of Array : ");
      int size = ui.nextInt();

      int [] arr = new int[size] ;
      System.out.print(" Enter Array Elements : ");

      for( int i = 0 ; i < size ; i++ ){
          arr[i] = ui.nextInt();
      }

    System.out.print(" Array Elements are : " );

      int sum = 0;

      for( int result : arr){

          System.out.print(result + " , ");

          sum = sum + result ;

      }

      System.out.println("  \n Sum of  Elements " + sum);

    }
}
