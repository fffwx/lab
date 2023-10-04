import java.util.Scanner;

public class Main {
    public static void main (String[] args) {
        int price;
        String productName;
        
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("enter a name of product: ")
        productName = scanner.nextLine();
        
        System.out.print("enter a price of product: ")
        price= scanner.nextInt();
        
        System.out.println("your producs:");
        System.out.println("name: " + productName);
        System.out.println("price: " + price);
    }
}