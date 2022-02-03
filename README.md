import java.io.*;
import java.lang.*;
import java.util.*;

class one {
    public void print_search()
    {
        System.out.println("Git");
    }
}

class two extends one {
    public void print_hub() { System.out.println("Hub"); }
}

public class Main {
    public static void main(String[] args)
    {
        two g = new two();
        g.print_search();
        g.print_hub();
    }
}
