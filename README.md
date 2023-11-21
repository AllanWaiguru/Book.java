import java.util.Scanner;
class Book

private String Title,Author,Publisher,Year of Publish,ISBN;

spublic void data_in()
{
Scanner read = new Scannert(System.in);

System.out.print("Enter the Title of the book: ");
Title = read.nextLine();

System.out.print("Enter the Author of the book: ");
Author = read.nextLine();

System.out.print("Enter the Publisher of the book: ");
Publisher = read.nextLine();

System.out.print("Enter the Year of Publish of the book: ");
Year of Publish = read.nextInt();

System.out.print("Enter the ISBN of the book: ");
ISBN = read.nextInt();
}
public void output()
{
System.out.println("\nTitle: "+Title);

System.out.println("\nAuthor: "+Author);

System.out.println("\nPublisher: "+Publisher);

System.out.println("\nYear of Publish: "+Year of Publish);

System.out.println("\nISBN: "+ISBN);

}
