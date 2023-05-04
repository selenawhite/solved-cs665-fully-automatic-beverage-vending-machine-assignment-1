Download Link: https://assignmentchef.com/product/solved-cs665-fully-automatic-beverage-vending-machine-assignment-1
<br>
1 Application Description

In this assignment, you will implement an application that controls a “Fully Automatic Beverage Vending Machine”. You are responsible to implement the controller software of this machine. The software should be able to control the brew process of different coffee and tea beverages. The machine should be able to




<ul>

 <li>brew Coffee sorts of Espresso, Americano, Latte Macchiato, and</li>

 <li>make Tea sorts of Black Tea, Green Tee and Yellow Tea.</li>

</ul>




When the machine stats up and is initiated, it shows a request question and ask users about their beverage wishes. After each brew process the state of the beverage machine should return to the same initial state and display the request question to ask users again. Note: There is no need to implement a graphical user interface (GUI), it is enough to show command line user interface.




You will create a controller for a beverage brewing machine. If this was a real-world application, your controller would process requests for different beverage types from the user interface, and would send status information or notifications to the UI (or the UI would query your controller for that information). Your controller will have the following functionality:

<ul>

 <li>→ The controller accepts orders to brew various coffees and teas [<em>Assignment Spec: Paragraph 1</em>]. See the assignment specification for the required beverage types. After the controller receives an order and successfully brews it, it should somehow indicate that the beverage was made. Once the beverage has been made by the machine, the controller must be ready to accept a new order.</li>

 <li>→ The machine will have a set of states, which may be explicit – using named states such as off/uninitialized/not-ready, on/initialized/ready, brewing, etc, which could then be queried – or implicit (based on what the machine is currently doing). The important thing is that once a beverage has been brewed, the controller is able to brew another beverage without needing to be reconstructed or reinitialized by the calling code.</li>

 <li>→ Optionally, the coffee machine can add condiments to the beverage order, such as milk and sugar. Each condiment can be added from zero to three times.</li>

</ul>

4.2. You are not required to create a user interface that accepts input. Instead, your beverage machine will have a programmatic interface –  an API – and you will use that API to test the operation of your machine. Your tests will be in the form of code in your main method that simulates a set of executions of your machine, and/or a set of JUnit tests.


