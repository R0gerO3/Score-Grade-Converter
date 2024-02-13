//Rodrigo Espinoza

/* goal
user enters 5 tests scores
output- avg test scores, letter grade of each test score,
, letter grade of avg test score*/
//create scanner object
/* create 2 non void methods
 calcAverage---> avg. of 5 test scores/use return
 determineGrade---->letter grade of each test score/use return*/
 //display overall grade of avg test score on main method

import java.util.Scanner;

public class Score_Converter
{
    public static void main(String[] args)
    {
        Scanner keyboard=new Scanner(System.in);
        System.out.println("Please enter the first test score.");
        double testScore1=keyboard.nextDouble();
        System.out.println("Please enter the second test score.");
        double testScore2=keyboard.nextDouble();
        System.out.println("Please enter the third test score.");
        double testScore3=keyboard.nextDouble();
        System.out.println("Please enter the fourth test score.");
        double testScore4=keyboard.nextDouble();
        System.out.println("Please enter the fifth test score.");
        double testScore5=keyboard.nextDouble();
        
        double average=calcAverage(testScore1,testScore2,testScore3,testScore4,testScore5);
        System.out.printf("Average test score is %.2f%%\n", average);

        
        String score1=determineGrade(testScore1);
        String score2=determineGrade(testScore2);
        String score3=determineGrade(testScore3);
        String score4=determineGrade(testScore4);
        String score5=determineGrade(testScore5);
        System.out.println("Test 1: "+score1);
        System.out.println("Test 2: "+score2);
        System.out.println("Test 3: "+score3);
        System.out.println("Test 4: "+score4);
        System.out.println("Test 5: "+score5);

        String gradeavg=determineGrade(average);
        System.out.println("Average grade: "+gradeavg);

        keyboard.close();
    }
    public static double calcAverage(double one, double two, double three, double four, double five)
    {
        double average1= (one+two+three+four+five)/5;
        return average1;
    }
    public static String determineGrade(double grade1)
    {
        String a="A";
        String b="B";
        String c="C";
        String d="D";
        String f="F";
        
        if (grade1>=90 && grade1<=100)
        return a;
        else if(grade1>=80 && grade1<=89)
        return b;
        else if(grade1>=70 && grade1<=79)
        return c;
        else if(grade1>=60&& grade1<=69)
        return d;
        else if(grade1<60)
        return f;
        else
        return "Invalid Score";
    }
}
