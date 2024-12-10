# FizzBuzz

Write a program that uses console.log to print all the numbers from 1 to 100, with two exceptions. For numbers divisible by 3, print "Fizz" instead of the number, and for numbers divisible by 5 (and not 3), print "Buzz" instead.

When you have that working, modify your program to print "FizzBuzz" for numbers that are divisible by both 3 and 5 (and still print "Fizz" or "Buzz" for numbers divisible by only one of those).


solution:

for (let result =1; result < 101; result++){
if (result % 3 ==0 && result%5 ==0){
    let result = "Fizzbuzz";
    console.log(result);
}   
   else if(result % 3 == 0){
        let result = "fizz";
        console.log(result)
    } else if 
     (result % 5 == 0){
        let result = "buzz";
        console.log(result)
    } 
    else {
        console.log(result)
    }
};