

//✅
//Question 7: Search Element in ArrayList
//Problem: Check if a specific element exists in ArrayList.
// Requirements:
//        ● Use contains() method
//● Return true/false or index
//Test Scenario:
//List: [10, 20, 30], Search: 20 → Output: Found at index 1


import java.sql.SQLOutput;
import java.util.ArrayList;
import java.util.Scanner;

public class Finding_Elements {

    public static void main(String[] args) {

        ArrayList< Integer > num = new ArrayList<>();

        Scanner ui = new Scanner(System.in );

        num.add(1);
        num.add(2);
        num.add(3);
        num.add(4);
        num.add(5);

        System.out.println(" Numbers in Elements are : " + num + " ,");

        System.out.println(" Entre Number to Find in Elements : ");
        int find = ui.nextInt();



        if(num.contains(find)){
            System.out.println(" found ");
        }
        else {
            System.out.println(" Not Found ");
        }


    }
}
