import java.util.ArrayList;

public class Book {
    private String title;
    private String author;
    private String publisher;
    private int year;
    private String ISBN;

    public Book(String title, String author, String publisher, int year, String ISBN) {
        this.title = title;
        this.author = author;
        this.publisher = publisher;
        this.year = year;
        this.ISBN = ISBN;
    }

    public String getTitle() {
        return title;
    }

    public String getAuthor() {
        return author;
    }

    public String getPublisher() {
        return publisher;
    }

    public int getYear() {
        return year;
    }

    public String getISBN() {
        return ISBN;
    }
}

public class LibraryCatalog {
    private ArrayList<Book> books;

    public LibraryCatalog() {
        books = new ArrayList<Book>();
    }

    public void addBook(Book book) {
        books.add(book);
    }

    public void displayBooks() {
        System.out.println("Title\tAuthor\tPublisher\tYear\tISBN");
        for (Book book : books) {
            System.out.println(book.getTitle() + "\t" + book.getAuthor() + "\t" + book.getPublisher() + "\t" + book.getYear() + "\t" + book.getISBN());
        }
    }
}
