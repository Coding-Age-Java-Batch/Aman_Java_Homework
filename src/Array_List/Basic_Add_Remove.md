

//  Question 6: Basic ArrayList Operations
//
//  Problem: Perform basic operations on ArrayList. Requirements:
//        ● Create ArrayList
//        ● Add elements
//        ● Remove and update elements

// Test Scenario:
// Add: "Java", "Python", "C++" → Remove "Python", Update "C++" to "Go"
//


import java.util.ArrayList;
import  java.util.Collection;

public class Basic_Add_Remove {
public static void main ( String [] args){

        ArrayList <String> input = new ArrayList<>();

        input.add(" Java ");
        input.add(" Python");
        input.add(" C++");

        System.out.println(" All Elements are : " + input);

        input.remove(1);
        System.out.println(" After Removing Element" + input);


    }
}
