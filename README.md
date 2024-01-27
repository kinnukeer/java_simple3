# java_simple3
import java.util.*;

public class Main {
    public static void main(String[] args) {
      LinkedList<String> l=new LinkedList<String>();
      l.add("CSE");
      l.add("ECE");
      l.add("IOT");
      l.add("MECH");
      l.add("AI");
      Collections.sort(l);
      System.out.println(l);
  }
}
