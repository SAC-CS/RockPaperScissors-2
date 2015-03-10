# RockPaperScissors
New to programming homework for class
import java.util.Scanner;

public class rockpaperscissor {

	public static void main(String[] args) {
	
	Scanner console = new Scanner(System.in);

	String choice = console.nextLine();
	
	if (isValid(choice)) {
		int aIchoice = (int)(Math.random()*3);
		int personChoice = getVal (choice);
		int rand = (int)(Math.random()*3);
		
	}
	else {
		System.out.println("Not Valid Input!");
	}
}	
	
	public static string didPersonWin(int pChoice, int computerChoice) {
		if (pChoice == 1) {
			if (computerChoice != 0) {
				if (computerChoice != 1) {
					return "Win";
				}
				return "Tie";
			}
			return "Lose";
		}
	}
	public static boolean isValid(String string) {
		if (string.equalsIgnoreCase("Rock")) {
			return true;
		}
		if (string.equalsIgnoreCase("Paper")) {
			return true;
		}
		if (string.equalsIgnoreCase("Scissor")) {
			return true;
		}
		public static int getVal (String string) {
			if (string.equalsIgnoreCase("Rock")) {
				return 0;
			}
		    if (string.equalsIgnoreCase("Paper")) {
		    	return 1;
		    }
		    else {
		    	return 2;
		    }
		}
	}
	
