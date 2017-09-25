# code-snippets
Example code for a variety of useful javascript algorithms

##Reverse a string
```
function FirstReverse(str) { 
    var splitString = str.split("");
    var reverseArray = splitString.reverse();
    var joinArray = reverseArray.join("");
  return joinArray;     
}
// keep this function call here 
FirstReverse('Hi my name is Janie');
```
##Find the factorial of a number
```
function FirstFactorial(num) { 

    var factorial = 1

    for (i = 1; i<= num; i++) {
        factorial = factorial*i;
    }
  // code goes here  
  return factorial; 
         
}
   
// keep this function call here 
FirstFactorial(8);
```

##Find the longest word in a sentence
```
function LongestWord(sen) { 
    var wordsList = sen.match(/[a-z0-9]+/gi);
    //This searches the sentence for characters matching letters or numbers but ignores punctuation, and returns it in an array.
    
    var sorted = wordsList.sort(function(a, b) {
    return b.length - a.length;
  });
    // the array sort function takes a function as a parameter
  // which is used to compare each element in the array to the
  // next element in the array

  return sorted[0];
    //The array now has a list of words in order of length, with the longest first.
    //So we just need to return the first word in the array.
}
   
// keep this function call here 
LongestWord("what is the longest word?");   
```
##Finding the sum of numbers in a series
```
function SimpleAdding(num) { 
    var sum = 0;
    for (var i=1; i <= num; i++) {
        sum = sum + i;
    }
  // code goes here  
  return sum; 
         
}
   
// keep this function call here 
SimpleAdding(readline());                            

//  return (num*(num+1))/2;
// this is an algorithm for finding the sum of a series of numbers
```



