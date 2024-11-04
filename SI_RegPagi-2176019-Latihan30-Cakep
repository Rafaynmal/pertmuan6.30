package pertemuan6;

/**
 *
 * @author Afra Syavina
 */
import java.util.Scanner;
public class Cakep {
    public static final String RESET = "\u001B[0m";
    public static final String RED = "\u001B[31m";
    public static final String GREEN = "\u001B[32m";
    public static final String YELLOW = "\u001B[33m";
    public static final String BLUE = "\u001B[34m";
    public static final String PURPLE = "\u001B[35m";
    
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);
        
        System.out.println(PURPLE + "Kamu ngerjain sendiri latihan 17 sampe latihan 30 ini?" + RESET);
        System.out.print("Jawab (Yoi/Enggak) : ");
        String jawaban = scanner.next().toLowerCase();
        
        System.out.println();
        
        switch (jawaban) {
            case "yoi":
                System.out.println(GREEN + "Cakep Bener."  + PURPLE + "Good Job" + RESET);
                break;
            case "enggak":
                System.out.println(RED + "Tetep cakep sih." + RESET);
                System.out.println(YELLOW + "Sing penting paham konsepnya yee." + RESET);
                System.out.println(BLUE + "Keep the code works dude" + RESET);
                break;
            default:
                System.out.println(YELLOW + "Jawaban tidak valid." + RESET);
                break;
        }

        scanner.close();

        }
    }

