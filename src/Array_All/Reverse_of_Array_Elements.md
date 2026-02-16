
// Question 2: Reverse Array
//  Problem: Reverse the elements of an array in-place.
 //  Requirements:
//  ● Swap elements from start to end using loop
//  ● Do not use extra array
//  Test Scenario:
//  Input: {1, 2, 3, 4} → Output: {4, 3, 2, 1}

import java.util.Scanner ;

class Reverse_of_Array_Elements{

public static void main ( String [] args ) {

Scanner ui = new Scanner ( System.in ) ;

System.out.print( " Enter Size of Array " ) ;
int size = ui.nextInt();

int [] arr = new int [size] ;

System.out.println ( " Enter " + size + " Elements" ) ;
for( int i = 0 ; i < size ; i++ ) {
 arr[i] = ui.nextInt();
 }

 System.out.print(" Entered Elements are :" );
 for( int i = 0 ; i <size ; i ++){
 System.out.print(arr[i] + " , " ) ;
 }

 for( int i = 0 ; i < size / 2 ; i ++ ){

    int rev = arr [i];
    arr[i] = arr[size - 1 - i ] ;
    arr[size - 1 - i ] = rev ;

 }

System.out.print("\n");
 System.out.print(" Reverse of Elements : " ) ;

 for( int i = 0 ; i < size ; i++){
 System.out.print(arr[i] + " , " ) ;
 }

}

}
