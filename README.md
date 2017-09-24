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
###Find the factorial of a number
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





