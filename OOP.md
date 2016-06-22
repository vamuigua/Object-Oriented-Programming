<h2>OBJECT ORIENTED PROGRAMMING</h2>
<p>-It asks "What things are in this program?"</p>
<p>-In OOP code,you define a Car Object and then list all of the functions it needs to perform.</p>
<p>-You define 2 new objects of the type car;all functions and varialbles would become capabilities that carA or carB would use bt. a and b would override and honk differntly</p>
<p>-If u want the car to drive differently in different terrain,OOP does not need to touch the working code bt. b4 jst types in a new function that gives the all-terrain capabilities.</p>
<p>-OOP code is alot neater & organised because if u want to add on a new capability u jst create a new function without touching any of the old code.</p>
<p>-OOP requires less code to get things done,because of a concept called **Inheritance**( the process that enables one class to acquire the properties (methods and variables) of another.)</br>
eg. First create a basc Car Object,then the objects carA and carB  are able to inherite all of the capabilities that all cars have while overridind those that differ.The car object above is refered to as the **SUPERCLASS**.</p>
<p>-A class is used to create addition objects having functions in the superclass.<br/>
<p>-Creating an Object:</p>
    className objectToCreate = new className();
        car dodge = new car();
</p>-Variables and methods are accessed using the <strong>dot</strong> operator(.) e.g To access the variable engine:</p>
          dodge.engine or dodge.getGas()
          
<p>-<strong>Encapsulating</strong> is creating 2 methods for each variable you define.One of the methodes returns the value(start method with get) while the other method changes the value of that variable(start methode with set).</br>
This is done to ensure that implementation details are not visible to users.</p>   
<p>-Advantages of Inheritance:</p>
<ol>
<li>1.Decreses duplicate code</li>
<li>2.Eliminates looking for what code needs to be changed<br/>
<li>3.Avoids breaking previously working code<br/>
<li>4.Simplifies your code overall.<br/>
</ol>
<p>-**Polymorphism**, which refers to the idea of "having many forms", occurs when there is a hierarchy of classes related to each other through inheritance,i.e</p>
      car dodge = new carA();//Declaring a object dodge to be of the superclass type instead of:
      carA dodge = new carA();
<p>-(Above)This allows you to create one function that automatically works with all subclasses of class car.</p>
<p>-Polymorphism provides you with a way to write code that doesn't depend on types;i.eThe methods in the superclass car will be in all the subclasses:<br/>
All of the subclasses of the car can drive foward, drive backward, stop;etc.</p>
<p>-Also, you woun't have to change the car class code & potentially break other parts of the programme.</p>
<p>-**Overloading Methods**<br/>
<p>-When methods have the same name, but different parameters e.g return type. no. of arguments or type of arguments e.g</p>
    int max(int a, int b) {
      if(a > b) {
        return a;
      }
      else {
        return b;
      }
    }
        
         OR<br/>

    double max(double a, double b) {
      if(a > b) {
        return a;
      }
      else {
        return b;
      }
    }

<p>-An Interface is just a shell class that provides the names of all the variables &methodes,but no code e.g</p>
    interface Vehcle{
      var engine;
      var gasTank;
      var door;
    driveFoward(var how Far);
    driveBackward(var how Far);
      stop();
      getGas();
      getGasTank();
    }








