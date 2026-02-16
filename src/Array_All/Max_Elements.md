//✅ Question 3: Find Maximum Element
// Problem: Find the maximum value in an array. 
//  Requirements:

//  ● Traverse the array using a loop
//  ● Compare and store max value
//Test Scenario:
//Input: {10, 5, 40, 25} → Outpu  t: 40

import java.util.Scanner;
class Max_Elements{
public static void main ( String[] args){

Scanner ui = new Scanner ( System.in);

System.out.print(" Entre Size of Array " );
int size = ui.nextInt();

int [] arr = new int [size] ;

System.out.print(" Entre Array Elements " );

for( int i = 0 ; i < size ; i++ ){
   arr[i] = ui.nextInt();
}
System.out.print(" Entred Elements are : " );
for( int i = 0 ; i < size ; i++){
System.out.print(arr[i] + " , " );
}

int max = 0 ;
for( int i = 0 ; i < size ; i++ ){
if( arr [i ] > max ) {
max = arr[i] ;
}
}
System.out.println( " \n  Max Element is : " + max);

}

}