# Style Sheet

#### 1) Comments

The comments need to follow this kind of pattern:
- Comments with one line only, should be made using '//' before it.
- Comments that have more than one line should be made between '/*' & '*/' like the following pattern

Example:

###### One line comment:
```java
	// One line comment 
```
###### Multiple lines comment:
```java
	/**
	* This
	* comment
	* has
	* multiple
	* lines
	*/
```

#### 2) Names: Classes, Attributes, Methods
The names for classes, attributes and methods should follow the java standard that's basically:

All classes, attributes or methods that have multiple names in it's composition should follow the pattern CamelCase, that consits in keep the initials of every word capitalized, without any underline or space between them.

Every variable needs to be declared in a separate line.

Example:

- Class:
	Starts with upper case.
	GamingMouse extends Mouse;

- Attribute:
	Starts with lower case.
	private double mouseButton;

- Method:
	Starts with lower case.
	public void setMouseButton;

- Constants:
	Only upper case.
	Only in this case the underscore is allowed.
```java
final int NUMBER_OF_HOURS_IN_A_DAY = 24;
```

#### 3) Identation
	
The identation of the code will follow the Java standard:

- The keys should start one space after the method parameters, class, control structures.
- The keys should end one line break after the scructure ends. 

Example:
```java
	public int anotherExample(parameters) {
```

- The identation standard used is 4 spacebars.

#### 4) Classes

The classes should stay in the following pattern:

- After the class name should be a blank space following the key starter '{'.
- Next line after the class opening should stay blank. 

Example:
```java
	public class ChocolateMilk {

	    // ...
	}	
```

#### 5) Control Structure: IF
	
- The parenthesis that starts the condition should have a blankspace after the if.
- There shouldn't be any white space before and after the start and ending of the parenthesis.
- There shouldn't be any space between operators.
- After the conditions there should be a blankspace before the key '{'.
- There should always be the use of keys no matter how many lines the if's body has.
- There should be a line break before the use of else or else if.

Example:
```java
	if (this.alcoholPercentage<5) {
	    System.out.println("Not dangerous overall");
	}

	else {
	    System.out.println("Potentially dangerous");
	}
```

#### 6) Control Structure: While

While should follow the same pattern used by "IF"

Example:
```java
while (dragonBabies<8) {
	System.out.println("No risk around this area.");
}
```

#### 7) Control Structure: For
	
The structure used by For follows the same pattern used by "IF".

- The semicolons should have a blankspace by their right. 

Example:
```java
for (int i=0; i<randomNumber; i++) {
    // God knows how long this'll take.
}
```

#### 8) Control Structure: Switch 
	
- The cases and the default should be indented.
- The statements for each case, or default, should stay in the following line and indented.

Examples:
```java	
switch (menu) {
    case 1:
        System.out.println("Omelette au Fromage");
        break;
    case 2:
        System.out.println("Mexican Paleta");
        break;

    // ...

    default:
        System.out.printn("Fancy food not found");
        break;
}
```

#### 9) Exceptions:
	
Should follow like the example:

Example:
```java
try {
    // do this...
}
catch (exception) {
    // do that...
}
```