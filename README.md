# Java Script Lecture 5

## Table of Contents 
+ Array
+ Destructuring
+ Spread & Rest

## What is Method in JavaScript ?
Aa method is a block of code which only runs when it is called. You can pass data, khown as parameters, into a method. Method are used to perform certain actions, and they are also known as functions.

## What is the Array in JavaScript ?
An array in JavaScript is a type of global object used to store data. Arrays can store multiple values in a single variable, which can condense and organize our code

## We have 18 methods in array
### 1 ) What is the push() in array
The push() method adds one or moreelements to the end of an array and returns the new length of the array

Example :

     let arr = [1, 2, "hello"]; 
     let add = arr.push(true, 4, 5);
     console.log(add); // 6
     console.log(arr); // [ 1, 2, "hello", true, 4, 5 ]
### 2 ) What is the pop() in array
The pop() method removes the last element from an array and returns that element. This method change the length of the array

Example : 

     let arr = ["a", "b", "c", "d", "e"];
     console.log(arr.pop()); // e
     console.log(arr); // [ "a", "b", "c", "d"]
### 3 ) What is the unshift() in array
The unshift method adds one or more elements to the beginning of an array and returns the new length of the array

Example : 

    let arr = [3, 4, 5]
    console.log(arr.unshift(1, 2)); // 5
    console.log(arr); // [ 1, 2, 3, 4, 5]
### 4 ) What is the shift() in array
The shift() method removes the first element from an array and returns that element. This method changes the length of the array

Example : 

    let arr = [3, 4, 5]
    let firstElement = arr.shift();
    console.log(firstElement); // 3
    console.log(arr); // [ 4, 5]
### 5 ) What is the toString() in array
The toString() method returns a string representation the specified array and its elements 

Example : 

    let arr = [3, 4, 5]
    console.log(arr.toString()); // ' 3, 4, 5 '
    
## JavaScript array methods 
### 1 ) IndexOf()
Example :

    let arr = ["apples", "banana", "dog", "bat"];
    let index = arr.indexOf("dog"); 
    console.log(index); // 2
    console.log(arr.indexOf("JS")); // -1
### 2 ) Includes()
Example :

    let arr = ["apples", "banana", "dog", "bat"];
    let isHere = arr.includes("dog"); 
    console.log(isHere); // true
    console.log(arr.includes("JS")); // false
### 3 ) Concat()
Example :

    let arr1 = [1, 2, 3]
    let arr2 = [4, 5, 6]
    console.log(arr1.concat(arr2)); // [ 1, 2, 3, 4, 5, 6 ]
### 4 ) Slice()
Example :

    let arr = ["book", "javaScript", "C#", "Css"];
    let sliced = arr.slice(1, 3); 
    console.log(sliced); // [ "javaScript", "C#" ]
### 5 ) Splice()
Example :

    let arr = [1, 2, 3, true, "Hello world!"];
    let b = arr.splice(1, 1, "apple", "cat"); 
    console.log(b); // [ 2 ] - deleted item 
    console.log(arr); // [ 1, "apple", "cat", 3, true ]
### This was the arrays method 

------------------------------------------------------------

                 The end of lecture 5
                   glat to see you
