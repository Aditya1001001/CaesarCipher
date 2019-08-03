# Ceaser Cipher

This is the soultion to the problem statement in the course 'Java Programming: Arrays, Lists, and Structured Data'.

## Task

*Create a new class called WordLengths. 
	* Write a void method countWordLengths that has two parameters, a FileResource named resource and an integer array named counts. This method should read in the words from resource and count the number of words of each length for all the words in resource, storing these counts in the array counts.
	* Write a method indexOfMax that has one parameter named values that is an integer array. This method returns the index position of the largest element in values . Then add code to the method testCountWordLengths to call indexOfMax to determine the most common word length in the file.
*Create a new class called ​CaesarCipher​
	* Write the method ​encrypt​ that has two parameters, a String named ​input​ and an intnamed ​key​. This method returns a string that has been encrypted using the CaesarCipher Algorithm.
	* Write the method ​encryptTwoKeys​ that has three parameters, a String named ​input​,and two integers named ​key1 ​and​ key2​. This method returns a String that has beenencrypted using the following algorithm. Parameter ​key1​ is used to encrypt every othercharacter with the Caesar Cipher algorithm, starting with the first character, and ​key2​ isused to encrypt every other character, starting with the second character. 
*Create a new class called CeaserBreaker​
	* Write a method decrypt that creates a new CeacserCipher object and uses the method encrypt to decypher text.
	* Write the method halfOfString in the CaesarBreaker class that has two parameters, a String parameter named message and an int parameter named start . This method should return a new String that is every other character from message starting with the start position.
	* Write the method getKey in the CaesarBreaker class that has one parameter, a String s. This method should call countLetters to get an array of the letter frequencies in String s and then use maxIndex to calculate the index of the largest letter frequency.
	* Write the method decryptTwoKeys in the CaesarBreaker class that has one parameter,a String parameter named encrypted that represents a String that was encrypted with the two key algorithm. This method attempts to determine the two keys used to encrypt the message, prints the two keys, and then returns the decrypted String with those two keys.

## What I learned
* More complicated operations on strings
* Using classes and objects to struture and reuse code