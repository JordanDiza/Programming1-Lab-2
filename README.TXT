Hello test test

Part II
#2 The value returned is 0 cents
#3 
When I insert money into the machine the value of the balance goes up.
There is no refund. They just steal the money
The ticket still prints
#4
Ticket still prints when the amount is lower than the ticket price
When I print the ticket the balance goes to 0
When I insert money the balance goes up
#5 
Machine 1= 100 & Machine 2 = 300
When a print a ticket for machine 1 the ticket price is 100 cents
When I print a ticket for machine 2 the ticket price is 300 cents
#6
public class Student
{
    
}
public class LabClass
{
    
}

#7 It does matter whether we write public class TicketMachine or class public TicketMachine in the outer wrapper class. The class diagram is all crossed up
#8 It is possible to leave out the word public
#9 It is not possible to leave out the word class
#10 
Fields: 
private int total;
private int balance;
private int price;
Method: public int getPrice()
Constructor: public TicketMachine(int cost)
    {
        price = cost;
        balance = 0;
        total = 0;
        
#11 There are no return type and its like the final product of a code bc it creates the final object
#12 It is the inner content of a class
#13 Inner content of a class
#14 Person, Game, Student, Server
#15 visibility modifier - type - variable name
#16 Yes because they expect a ";" or else its an error
#17 public int status;
#18 student class
#19 There are 2 String title and double price
#20 Yes
#21 public Pet(String petsName) 
{ 
    name = petsName 
} 
#22 public Date(String month, int day, int year)
#23 They are the same expect for the method name
getPrice returns the price field
while getBalance returns the balance field
#24 How much money did you put in the machine?
#25 No the return statement in the body of the method does not need any changing in order to complile it.
#26 public int getTotal()
    {
        return total;
    }
#27 It says missing return statement
#28 There is no return statement for printTicket
#29 No because, they both dont have a return statement
The printTickets simulate the printing of a ticket, there is no return
The return type is "void"
#30 getBalance = 0
insertMoney= 50
balance= -50
#31  
/ public void increaseScore(int points) 
{ 
    score = score + points ;
    }
#32 Yes it is a mutator since it changes the number of credits.
#33 public void discount(int amount)
{
    price = price - amount;
}
#34 public void setAge(int currentAge)
age = currentAge;
#35 public void setAlive(boolean status)
{ 
    alive = status;
}
#36  
public TicketMachine(int price)
    {
        price = price;
        balance = 0;
        total = 0;
    }
#37 My cat has green eyes.
#38 public void prompt()
    
    {
       //Please insert the correct amount of money. 
    System.out.println("Please inser the correct amount of money.");
    }
#39 # price cents.
#40 # price cents.
#41 public void showPrice()
{
    System.out.println)("The price of a ticket is" + 200 + "cents:"
}
#42 Dont understand
#43 public void printTicket()
    {
        // Simulate the printing of a ticket.
        System.out.println("##################");
        System.out.println("# The BlueJ Line");
        System.out.println("# Ticket");
        System.out.printf("# %d cents.%n", price);
        System.out.println("##################");
        System.out.println();

        // Update the total collected with the balance.
        total = total + balance;
        // Clear the balance.
        balance = 0;
    } 
**had to change those curly quotation marks
#44 public TicketMachine()
    {
        price = 1000;
        balance = 0;
        total = 0;
    }
The object automatically create by it self without me having to type the ticket price.
#45 public TicketMachine(int price)
    {
        this.price = price;
        balance = 0;
        total = 0;
    }
#46 public void Empty()
{
    total = 0
}
it doesn't need any parameters because the the total field is 0 and there is no call method needed here?
t is a mutator since it changes the value of the ticket when I empty it
It modifies the total to 0 after emptying it
