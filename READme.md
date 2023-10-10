*  **Collections**
* A Collection is an object that holds references to other objects. These are data structures and the objects within the collection are known as elements.
* Java provides a collections framework which consists of interfaces, classes and methods to store and manipulate aggregate data.
* Some collections allow duplicate elements, while others require every element to be unique. Some collections are ordered, while others are not.
* Collection itself is an interface and is the root of the hierarchy. Java does not provide any direct implementations of the Collection interface, but there are other interfaces which inherit from Collection.
 
* ** Set**
* Set is a collection which cannot contain duplicate elements.
* An example use case for Set would be a standard deck of 52 playing cards, where each card would be an element in the collection and each of them are unique.
* Ex: Set fruit = new HashSet();
  fruit.add("apple");
  fruit.add("lemon");
  fruit.add("banana");
  fruit.add("orange");
  fruit.add("lemon");

            System.out.println(fruit.size());
            System.out.println(fruit);
        

# **List**:

* List is a collection where the elements are ordered. List can contain duplicate elements.
* An example of where List might be used would be the phone numbers from your call history. They are listed in order and some numbers may appear more than once.
* Ex:List fruit = new ArrayList();
  fruit.add("apple");
  fruit.add("lemon");
  fruit.add("banana");
  fruit.add("orange");
  fruit.add("lemon");

            System.out.println(fruit.get(2));
            System.out.println(fruit.size());
            System.out.println(fruit);

# **Queue**
* Queue is a collection of ordered elements, which is typically used to hold items that are going to be processed in some way.
* An example use case would be the people in the checkout line at a supermarket. People who are new to the queue are added at the end and the processing of the queue is handled from the beginning. This type of processing is well known as first in-first out (FIFO).
EX:Queue fruit = new LinkedList();
  fruit.add("apple");
  fruit.add("lemon");
  fruit.add("banana");
  fruit.add("orange");
  fruit.add("lemon");

            System.out.println(fruit.size());
            System.out.println(fruit);

            fruit.remove();
            System.out.println(fruit);

            System.out.println(fruit.peek());

# **Map**
* Then finally we have Map, which is not a true collection, meaning it does not inherit from the Collection interface. However, it contains collection-like operations, which enable them to be used as collections. Maps are used to hold key/value pairs.
* An example for this would be a list of bank transactions where each Map entry has a unique transaction ID serving as the key and the value would be the actual transaction object
* EX:Queue fruit = new LinkedList();
  fruit.add("apple");
  fruit.add("lemon");
  fruit.add("banana");
  fruit.add("orange");
  fruit.add("lemon");

            System.out.println(fruit.size());
            System.out.println(fruit);

            fruit.remove();
            System.out.println(fruit);

            System.out.println(fruit.peek());