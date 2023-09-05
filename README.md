import java.util.*;

public class CollectionDemo { public static void main(String[] args) {

    Set<String> set = new HashSet<>();
    set.add("Rupesh");
    set.add("Virat");
    set.add("Rohith");
    set.add("Hardik"); 
    System.out.println("Set: " + set);

 
    List<Integer> list = new ArrayList<>();
    list.add(1);
    list.add(2);
    list.add(3);
    list.add(2); 
    System.out.println("List: " + list);

  
    Map<Integer, String> map = new HashMap<>();
    map.put(1, "One");
    map.put(2, "Two");
    map.put(3, "Three");
    map.put(2, "Duplicate");
    System.out.println("Map: " + map);

    int secondElement = list.get(1);
    String valueForKey2 = map.get(2);
    System.out.println("Second element in List: " + secondElement);
    System.out.println("Value for key 2 in Map: " + valueForKey2);
}
}
