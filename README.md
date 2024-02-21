# Object Methods

**Definition**: 
* Object methods are actions that can be perfomred on object (Reference: W3)
* It is a property containing 'function definition'

**What this script demonstrates?**
* These codes encapsulate functionalty related to that Object
* It shows how we can interact with the property of Object using 'This'

**We can break the scripts down into 4 steps**
1. Object Creation:
   * LightBulb is created as a constant variable using 'const'
   * It is an object literal, defined within curly braces {}
   * Inside the object, there are two properties:
     * isOn = initialized to false
     * turnOn and turnOff = these are methods (functions) defined as properties of the object
    
2. Methods:
    * turnOn is a method that sets the isOn property of the lightBulb object to true.
    * It logs a message to the console indicating that the light bulb is now on.
    * turnOff is a method that sets the isOn property of the 'lightBulb object to false.
    * It logs a message to the console indicating that the light bulb is now off.
  
3. Using Object Methods:
   * lightBulb.turnOn() is called and invokes the turnOn method of the lightBulb object.
   * It set isOn to true and logs 'The light bulb is now on' to the console.
   * lightBulb.turnOff() is called which invokes turnOff method.
   * It set isOn to false and logs 'The light bulb is now off.' to the console.
  
4. Outputs:
   * After calling lightBulb.turnOn()  we can see the strings followed by 'true' printed on the console by console.log(lightBulb.isOn)
   * After calling lightBulb.turnOff()  we can see the strings followed by 'false' printed on the console by console.log(lightBulb.isOn)


