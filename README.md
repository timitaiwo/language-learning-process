# Language Learning Process

Using examples largely gotten from the below video and previous experience, this repository summarizes a process of learning or getting familiar with a programming language.
https://youtu.be/87SH2Cn0s9A?si=LcluVxABoh2NW0bj

## Basic Language Constructs
1. Printing to terminal/commandline 
2. variable deceleration and datatypes
3. operators (e.g arithmetic. logic and tenary) _[1]_
4. conditional statements (if, if/else etc.)
5. loops (for, while etc.)
6. Collection objects e.g List/Arrays, Set etc.
7. input/output (accepting user input mostly)
8. files (reading from and writing to files)


_[1] arithmetic operators represent addition, subtraction etc. logical operators represent AND, OR etc._

## Intermediate stuff
8. functions and parameters/arguements
9. Classes/Struct
10. Memory management e.g Allocators, Constructors etc.
11. decorators

## Beginner Exercises (increasing difficulty)
The below exercises can be used to get familiar with the syntax of a language and can be done with the various level of user interactivity. Write a program that does the below:
1. Calculate the circumference of a circle - 2*PI*r.
2. Implement and use Pythagoras theorem in a program i.e x^2 = y^2 + z^2.
3. Convert a given temprature unit from Celcius to Farenheight or from Farenheight to Celcius depending on the user input (conditional statements).
4. A calculator that takes two inputs and an operator and performs the associated mathematical operation e.g inputs '6', '4' and '+' would output 10 as 6+4=10. This can be done with and without using functions/procedures. (conditional/switch statements).
5. Takes a temprature measurement and prints if the temprature is hot, cold or warm depending on the value. Hot, cold and warm values fall within ranges (conditional statements).
6. Request a piece of information from a user a given number of times and give a response either when the correct information is passed or the request has been made that number of times. (loops).
7. Request a piece of information from a user and repeat the request until the user give an acceptable response (loops).
8. Iterate over a list/array and print each of it's elements to the screen/terminal. e.g [6, 12, 24, 48, 96] or it's floating point equivalent. (collection objects).
9. _(optional/language dependent)_ Given an array/list [1, 2, 3, 4, 5] remove 4 from the array to give [1, 2, 3, 5]. Then add 6 to give [1, 2, 3, 5, 6]. (mutable collection objects).
10. Given the below 2D array/list
    ```python
    [
      [1, 2, 3],
      [4, 5, 6],
      [7, 8, 9]
    ]
    ```
    Sum up the elements in each row to get
     ```python
    [
      [6],
      [15],
      [24]
    ]
    ```
    Get the mean of the elements in each row to get
     ```python
    [
      [2],
      [5],
      [8]
    ]
    ```
     
12. For the same 2D array,
    ```python
    [
      [1, 2, 3],
      [4, 5, 6],
      [7, 8, 9]
    ]
    ```
    sum up the elements in each column to get,
     ```python
    [
      [12, 15, 18]
    ]
    ```
    Get the mean of the elements in each row to get,
     ```python
    [
      [4, 5, 6]
    ]
    ```
14. Implement the functionality of all above exercises as functions.
15. Implement a class or struct that represents a person who has a name and an age.
16. Implement a class or struct that represents a player of a a club. The class/struct has a name, age, club, player number and an array of previous played numbers. Inheritance should be used if possible.
17. _(language classes)_ Implement methods/functions for the player in above exercise. The player could be running, walking or jogging. Implement a function(s) that would print to terminal the status of the player.

x. implement  three sorting algorithms to sort the array/list ```[4, 3, 7, 7, 0, 5]``` (functions)
