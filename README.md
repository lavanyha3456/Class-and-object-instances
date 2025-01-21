# Class-and-object-instances
class Person {

// Attributes of the class

String name;

int age;

// Constructor to initialize the object

Person(String name, int age) {

this.name = name;

this.age = age;

}

// Method to display details

void displayInfo() {

System.out.println("Name: " + name);

System.out.println("Age: " + age);

}

}

public class ClassAndObjectExample {

public static void main(String[] args) {

// Create an object of the Person class

Person person1 = new Person("keerthana", 17);

// Access the object's method

person1.displayInfo();

// Create another object of the Person class

Person person2 = new Person("deepthi", 17);

// Access the object's method

person2.displayInfo();

}

OUTPUT:

Name: keerthanaAge: 17

Name: deepthi

Age: 17
