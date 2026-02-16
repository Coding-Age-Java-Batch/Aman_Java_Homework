
//✅ Question 7: Search Element in ArrayList
//Problem: Check if a specific element exists in ArrayList. 
//Requirements:
//● Use contains() method
//● Return true/false or index
//Test Scenario:
//List: [10, 20, 30], Search: 20 → Output: Found at index 1

import java.util.ArrayList ;

class Find_Elements{
public static void main ( String [] args ){

ArrayList < Integer > num = new ArrayList <> () ;

num.add(5) ;
num.add(6);
num.add(7);
num.add(8);
num.add(9);

System.out.print(" Array Elements are : " + num );

if( num .contains(9)){
System.out.print(" Elements is Present " );

}

else{
System.out.print(" Element is Not present ");
}




}


}