import java.util.Scanner;


class Books {
    String title;
    String author;
   double price;
    String ISBN;
    int stock;

    void Display() {
        
        System.out.println("Book's Name : " + title);
        System.out.println("Author : " + author);
        System.out.println("Price : " + price);
        System.out.println("ISBN : " + ISBN);
        System.out.println();
    }
    
    void Availability(){
        if (stock >0) {
    System.out.println("The Book :" + title + " is Available");
} else {
    System.out.println("The Book :" + title + " Not available");
}
    }
    
    
    void restock( int amt) {
        stock = stock+amt;
        System.out.println("The Book : " + title + " has been added in stock by : " + stock);
        System.out.println();
        
    }
    
    void Add_discount(double percent){
        price=price-price*(percent/100);
        System.out.println("The discount applied to book : "+title+" . The final price of the book is : $" +price);
        
    }
}




public class Ass1{

    public static void main(String[] args) {

       
        System.out.println("Books Inventory:");
        System.out.println();
        
       
        Books b4 = new Books();
        b4.title = "daaaa";
        b4.author = "kkll";
        b4.price = 900;
        b4.ISBN = "kok89890hh";
        b4.stock=18;
        
        Books b1 = new Books();
        b1.title = "abcsd";
        b1.author = "bhjhgbgh";
        b1.price = 500;
        b1.ISBN = "tfftuyuyty6";
        b1.stock=0;

       
        b1.Display();
        b4.Display();
        
        b1.Availability();
         b4.Availability();
         
         b1.restock(3);
         b1.Add_discount(15);
        System.out.println();
        
        
        
    }
}
