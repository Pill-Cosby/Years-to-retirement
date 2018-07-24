# Years-to-retirement
Getters and Return value

public class HelloWorld{

class person {
    String name
    int age;
    
    void speak;
    System.out.println("My name is" + name);

}
    int calculateYearsToRetirement(); {
        int yearsLeft = 65 - age;
        
        return yearsLeft;    
    }
    
    int getAge(); {
        return age;
    }
    String getName(); {
        return name;
    }
    
     public static void main(String []args){
         person person1 = new person();
     
         person.name = "David";
         person.age = "30";
         person.speak ();
     
         int years = person1.calculateYearsToRetirement();
         
         System.out.println("Years to go before retirement " + years);
         
         int age = person1.getAge();
         
         String name = person1.getName();
         
         System.out.println("Name: " + name);
         System.out.println("Current age is: " + age);
     }
     
}
