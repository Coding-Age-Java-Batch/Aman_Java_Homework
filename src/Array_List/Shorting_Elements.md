
//Question 8: Sort an ArrayList
//Problem: Sort an ArrayList of integers in ascending order.
//Requirements:
//● Use Collections.sort()
//Test Scenario:
//Input: [4, 1, 3, 2] → Output: [1, 2, 3, 4]

import java.util.ArrayList;
import java.util.Collections;

class Shorting_Elements{

public static void main ( String [] args) {

ArrayList < Integer > num = new ArrayList <> () ;

num.add(1);
num.add(5);
num.add(3);
num.add(2);
num.add(4);

System.out.print(" Numbers before Shorting : " + num);

Collections.sort(num);

System.out.println();

System.out.print(" Number  after Shorting : " + num);






}



}