import java.util.Scanner;

class caculator {
    
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.println("What is the first number: ");
        int x = scanner.nextInt();
        
        System.out.println("What is the second number: ");
        int y = scanner.nextInt();
        
        
        System.out.println("What do you want to do: ");
        char solve = scanner.next().charAt(0);
        
        
        if(solve == '+'){
            System.out.println(x + y);
        }
        else if(solve == '-'){
            System.out.println(x - y);
        }
        else if(solve == '*'){
            System.out.println(x * y);
        }
        else if(solve == '/'){
            System.out.println(x / y);
        }
    }
}
