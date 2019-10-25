#
# DiceRoller

#
# Project Summary

This application rolls 5 individual dies. After they are rolled, each die gets its face value returned to the user as a string.

.

#
# Running the Program

The program requires a compiler compliance level of Java 1.7 to run.

To execute the program simply download the repository, compile the code, and run.

.

#
# Classes Documentation

DiceRoller contains 2 classes, a Die class and a Main class.

### **Class: Die**

This class takes an n sided die and rolls it, gets the face value of the die, and gets the number of faces of the die

**Constructor**

Die(int numfaces)

_\*\*Creates an empty Event._

#### **Attributes**

| **Attribute** | **Description** |
| --- | --- |
| private int numFaces  | The number of faces of the die rolled |
| private int faceValue  | The face value of the die rolled |

#### **Methods**

| **Returns** | **Method** |
| --- | --- |
| int | **roll()** |
|   | _A method used by the class Die that rolls the created die._ |
| int | **getFaceValue** () |
|   | _Returns the faceValue of the die rolled._ |
| int | **getNumFaces** () |
|   | _Returns the numFaces of the die rolled._ |
| String | **toString** () |
|   | _Returns the die rolled and its faceValue as a string._ |

### **Class: Main**

This main class will use the Die classes methods to roll 5 separate dies, chosen from the set **[d4, d6, d8, d10, d12, d20, d100]****, **** and return each rolled die&#39;s face value to the user**

#### **Methods**

| **Returns** | **Method** |
| --- | --- |
| void | **main(String[] args)** |
|   | _Rolls 5 die at random and stores each in an ArrayList. Then, each die rolled has its faceValue returned to the user as a string_ |
