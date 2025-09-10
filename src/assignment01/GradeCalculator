import java.util.Scanner;

public class GradeCalculator {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        System.out.print("Enter student name: ");
        String name = in.nextLine();

        System.out.print("Enter number of studios attended (0-15): ");
        int studiosAttended = in.nextInt();

        System.out.print("Enter average quiz grade (0-100): ");
        double averageQuizGrade = in.nextDouble();

        System.out.print("Enter average exam grade (0-100): ");
        double averageExamGrade = in.nextDouble();

        double weightedStudioGrade = ((double)studiosAttended / 15) * 15;
        double weightedQuizGrade = (averageQuizGrade / 100) * 25;
        double weightedExamGrade = (averageExamGrade / 100) * 60;
        double totalGrade = weightedStudioGrade + weightedQuizGrade + weightedExamGrade;

        System.out.println("CSE131 Grade for: " + name);
        System.out.println("Number of studios attended: " + studiosAttended);
        System.out.printf("Weighted studio grade (out of 15): %.2f\n", weightedStudioGrade);
        System.out.printf("Average quiz grade: %.2f\n", averageQuizGrade);
        System.out.printf("Weighted quiz grade (out of 25): %.2f\n", weightedQuizGrade);
        System.out.printf("Average exam grade: %.2f\n", averageExamGrade);
        System.out.printf("Weighted exam grade (out of 60): %.2f\n", weightedExamGrade);
        System.out.printf("Total Grade: %.2f\n", totalGrade);

        in.close();
    }
}
