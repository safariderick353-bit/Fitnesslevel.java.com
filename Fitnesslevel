import java.util.Scanner;

public class FitnessLevel {

    public static String getFitnessLevel(int steps) {
        if (steps >= 10000) {
            return "excellent";
        } else if (steps >= 7000) {
            return "good";
        } else if (steps >= 4000) {
            return "average";
        } else {
            return "poor";
        }
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter your steps for today: ");
        int dailySteps = scanner.nextInt();

        String fitnessLevel = getFitnessLevel(dailySteps);

        System.out.println("Your fitness level: " + fitnessLevel);

        scanner.close();
    }
}
