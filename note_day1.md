# Mobile Application Development

A mobile application is a software system designed to run on mobile computing devices with limited resources. Mobile applications should be designed to consume fewer resources, such as battery power, memory, and processing power, while maintaining continuous operation and providing the intended functionality.

 Mobile applications are often preferred over web applications because:

- Offline support: Mobile applications can work without a network connection. When a connection becomes available, the application can synchronize data with a central server.
- Access to hardware and OS features: Mobile applications run directly on the mobile operating system rather than inside a web browser. This gives them efficient access to device features such as the camera, GPS, sensors, Bluetooth, and storage.
- Easy accessibility: Users can open a mobile application by tapping its icon instead of entering a URL or following a web link.

---

## Immutable Variables 

Varibales are declared using `` val `` keyword are referred immutable becasue their values can't be modified after initilization They can be considered as read only varibales.

## Mutable Varibales

Varibales declared using ``var`` keyword considered to be mutable becasue their values can be modified during program execution they support *read and write* operations.

## Type Inference rule

Kotlin compiler is capable of determining the data type of the variable when a variable is initialized during its declaration . we can skip the data type if the variable is initialized when it is declared.

```
Syntax
<val/var> <variable-name> : <Data Type>

Type Inference Rule 
Syntax 
<val/var> <variable-name> = <value>;
Var name = “John”

```
---
## Types of Arguments in method 

### Postional Arguments

Are values pass into a function fullowing the order of the parmenters mesction in function declaration the function assings the values the parametrs based on their order.

- ex :

```
    finalbill(100, "name");
```
### Named Arguments

Allowa u to pass values into function by expelsitly mentioning the parameter name along with it's value this approach improves code readbillity while allowing you to invock the function by passing values onto paramters in any order.

- ex:

``` 
    finalbill(amount=100,name="name");
```

---
## Default Parameter


A default Paramter is a parmeter decaler with a default value if a value is not fast for a parameter with a default value during method invocation the default will be used for the parameter it allows us to declare optional parameters in a funtion it can be used to readuce the needs for method overloading.


