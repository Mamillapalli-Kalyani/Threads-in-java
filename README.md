# Threads-in-java
public class Main
{
  public static void main(String args[])
  {
    ThreadProgram t1 = new ThreadProgram();
    ThreadProgram t2 = new ThreadProgram();
    t1.start();
    t2.start();
  }
}
