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
     public static void main(String []args){
         person person1 = new person();
     
         person.name = "David";
         person.age = "30";
         person.speak ();
     
         int years = person1.calculateYearsToRetirement();
         
         System.out.println("Years to go before retirement " + years);
     }
     
}
