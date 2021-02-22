# LOCAL STORAGE 

## What is localStorage?

* localStorage is a property that allows JavaScript sites and apps to save key/value pairs in a web browser with no expiration date. This means the data stored in the browser will persist even after the browser window is closed.

## How does localStorage work?

* To use localStorage in your web applications, there are five methods to choose from:

setItem(): Add key and value to localStorage.
getItem(): This is how you get items from localStorage.
removeItem(): Remove an item by key from localStorage.
clear(): Clear all localStorage.
key(): Passed a number to retrieve the key of a localStorage.

## setItem(): How to store values in localStorage

* It takes two parameters: a key and a value. The key can be referenced later to fetch the value attached to it.

## getItem(): How to get items from localStorage

* To get items from localStorage, use the getItem() method. getItem() allows you to access the data stored in the browser’s localStorage object.

getItem() accepts only one parameter, which is the key, and returns the value as a string.


## removeItem(): How to delete localStorage sessions

* To delete local storage sessions, use the removeItem() method.

When passed a key name, the removeItem() method removes that key from the storage if it exists. If there is no item associated with the given key, this method will do nothing.



## clear(): How to delete all items in localStorage

* Use the clear() method to delete all items in localStorage.

This method, when invoked, clears the entire storage of all records for that domain. It does not receive any parameters.


## key(): How to get the name of a key in localStorage

* The key() method comes in handy in situations where you need to loop through keys and allows you to pass a number or index to localStorage to retrieve the name of the key.






