# Advance-programming-assignment-5th
Write a class Book with attributes title and author. Add a method to display book info.
public class Book {
    private String title;
    private String author;

    public Book(String title, String author) {
        this.title = title;
        this.author = author;
    }

    
    public void displayInfo() {
        System.out.println("Title: " + title);
        System.out.println("Author: " + author);
    }

    public static void main(String[] args) {
        Book myBook = new Book("1984", "George Orwell");
        myBook.displayInfo();
    }
}
