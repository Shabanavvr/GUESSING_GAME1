# GUESSING_GAME1
import java.util.Scanner;
import java.lang.Math;
public class Guess
{
public static void main(String[] args)
{
// my guess number is between 1-100

int guess_num=(int)(Math.random() *100)+1;
Scanner sc=new Scanner(System.in);

// the number of times the user can try is
int t=4;
System. out.println("Enter your guess: ");
            int guess = input.next();
            // if the user guesses correctly, print the congratulation message and exit the program
            if (guess == answer) {
                System. out.println("You guessed the number!\nYou win!");
                break;
            }
            // if the user guesses greater than the number, print the message and reduce the number of
            // trials
            else if (guess > answer) {
                System.out.println("Your guess is too high.\nYou have " + (k - 1) + " tries left.");
                k--;
            }
            // if the user guesses less than the number, print the message and reduce the number of
            // trials
            else {
                System.out.println("Your guess is too low.\nYou have " + (k - 1) + " tries left.");
            }
            // after each trial decrease the number of trials by 1
            t--;
        }
    // if the user has run out of trials, print the message and exit the program

		if (correct==false) {
        System.out.println("You ran out of tries.\nYou lose!");
    }
    }
}
