# milestones1
adding

package assignment12;

import java.util.Scanner;

public class Assignment12 {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int starting_number , ending_number;
        System.out.print("Enter starting_number :");
        starting_number = input.nextInt();
        System.out.print("Enter ending_number :");
        ending_number = input.nextInt();
        
        if(starting_number<=ending_number){
        int sum_of_numbers=0; 
        for (int i = starting_number; i <=ending_number; i++) {
            //System.out.println(i);
            //sum_of_numbers =i+i ;
            System.out.println("i ="+i);
            sum_of_numbers=sum_of_numbers+i;
            //System.out.println(sum_of_numbers);
            System.out.println("Sum previous all  number "+sum_of_numbers);
        }
        System.out.println("\"Sum of all numbers :"+sum_of_numbers);
        
    }
        else{
            System.out.println("starting_numben should less than ending_number");
        }
        
        
    }
    
}
