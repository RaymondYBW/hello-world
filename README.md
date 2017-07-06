# hello-world
My first try of Github


public class HelloWorld
{
  public static void main (String [] args)
  {
    System.out.println("Please enter the string")
    String input = sc.nextLine();
    if(trager(input))
    {
      System.out.println("Hello, world!");
    }
  }
  
  public static boolean trager(String input)
  {
    if(input.euqal("Hello, world!"))
    {
      return true;
    }
    else
      return false;
  }
}
