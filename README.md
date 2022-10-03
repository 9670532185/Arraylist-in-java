# Arraylist-in-java
//Arraylist is used only objects ex.Integer,String not used primerive data types ex.int ,float//
import java.util.ArrayList;
import java.util.*;
public class Arraylist {
    public static void main (String[] args)
    {
        ArrayList<Integer> obj=new ArrayList<>();//create arraylist
        //add function
        obj.add(23);
        obj.add(4);
        System.out.println(obj);
        //add elements in between
        obj.add(1,11);//(index,elements)
        System.out.println(obj);
        //delete elements //
        obj.remove(2);
        System.out.println(obj);
        //find the size of list
        System.out.println(obj.size());
        //Sorting a list //using Collentions class
        Collections.sort(obj);
        System.out.println(obj);

    }
    
}
