# problemsolving


Create a function that takes two numbers as arguments and returns their sum.
Write a function that takes an integer minutes and converts it to seconds.
Create a function that takes a number as an argument, increments the number by +1 and returns the result.
Create a function that takes the age in years and returns the age in days.
sniCreate a function that takes voltage and current and returns the calculated power.
Write a function that returns the string "something" joined with a space " " and the given argument a.
Create a function that takes two arguments. Both arguments are integers, a and b. Return true if one of them is 10 or if their sum is 10.
Create a function that takes two strings as arguments and returns either true or false depending on whether the total number of characters in the first string is equal to the total number of characters in the second string.
Create a function that takes a name and returns a greeting in the form of a string. Don't use a normal function, use an arrow function.
Create a function that takes an array of 10 numbers (between 0 and 9) and returns a string of those numbers formatted as a phone number (e.g. (555) 555-5555).
Create a function that returns an array of strings sorted by length in ascending order.
Example:
sortByLength(["a", "ccc", "dddd", "bb"]) ➞ ["a", "bb", "ccc", "dddd"]

Create a function that takes an array of arrays with numbers. Return a new (single) array with the largest numbers of each.
Example:
findLargestNums([[4, 2, 7, 1], [20, 70, 40, 90], [1, 2, 0]]) ➞ [7, 90, 2]

Create a function that takes an array of numbers and returns the second largest number.
Example:
secondLargest([10, 40, 30, 20, 50]) ➞ 40


Create a function that takes an array of items, removes all duplicate items and returns a new array in the same sequential order as the old array (minus duplicates).
Example:

removeDups([1, 0, 1, 0]) ➞ [1, 0]

removeDups(["The", "big", "cat"]) ➞ ["The", "big", "cat"]

Create a function that takes an array of integers as an argument and returns a unique number from that array. All numbers except unique ones have the same number of occurrences in the array.

Example:

findSingleNumber([2, 2, 2, 3, 4, 4, 4]) ➞ 3

Create a function that takes two strings as arguments and returns the number of times the first string (the single character) is found in the second string.
Example:

charCount("c", "Chamber of secrets") ➞ 1

Create a function that takes a string and returns the number (count) of vowels contained within it.
Example:

countVowels("Celebration") ➞ 5

Given a string, create a function to reverse the case. All lower-cased letters should be upper-cased, and vice versa.
Example:
reverseCase("Happy Birthday") ➞ "hAPPY bIRTHDAY"

  Take one integer n, loop till n and pass each value to a function, create a function that takes one integer parameter, and multiply with 2 in every integer.
			
			Input:      n=5
			Output:   2 4 6 8 10

			Explanation:  Loop start with 1 go till 5 bcoz n=5
					1 x 2 =2, 2 x 2=4, 3 x 2=6 …..etc 


 20. Create Function that will take one parameter and return type of the data.
			
			Input:       500
			Output:     Integer

			Input:       Coding
			Output:    String


 21. Program to find greatest of three numbers(using ternery operator).

			Input:  4 8 2
			Output: 8 is gretest

 22 . C Program to find factorial of number.
		
			Input: n=5
			Output: 120

			Explanation: 5 x 4 x 3 x 2 x 1 = 120
	
 23. C Program to arrange numbers in ascending order
			Input: [2,3,1,5,4]
			Output: [1,2,3,4,5]

		        Sort the Array using loop only(you can not use predefined function).

 24. Print Patter using loop.

			1
			1 2
			1 2 3
			1 2 3 4
  			1 2 3 4 5

	
 25. C Program to Calculate the Power of a Number(using loop only).

			Input: n=5, p=3
			Output: 5 ^ 3 = 125
			Explanation: 5 x 5 x 5 = 125

 26. Program to Check Whether a Number is Prime or Not

			Input: 9
			Output: 9 is not a prime no

			Input: 7
			Output : 7 is a prime no


 27. Program to find LCM of two numbers using while loop

			Input: 15 50
			Output: Lcm of 15 and 50 is 150.


 28. Program to Display Characters from A to Z Using Loop with count.

			Output: A1 B2 C3 D4 E5 F6 ……. Z26 


29. Program to find a missing number

			Input:  n=5(length of array), arr= [5,3,1,4]
			Output: 2 is missing

		Using loop only(you can not use predefined function)


30. Program to count vowels and consonants in a given String.

			Input: i am ram
			Output: 3 vowels 3 consonants.



31. program to insert  the elements of an array for specific index.

			Input: [1,2,3,4,5,7,8,9,10] , index=5
			Output: [1,2,3,4,5,6,78,9,10]



32. Reverse a number using while Loop

			Input: 123
			Output: 321


33. Count occurrence of number:

			Input: [1,6,3,1,5,9,7,2,1,9,3,7,8,9,10] , no find=7
			Output: 7 present 2 times.










Difficulty Level : Medium

Write a function that converts an object into an array, where each element represents a key-value pair in the form of an array.

Examples :

toArray({ a: 1, b: 2 }) ➞ [["a", 1], ["b", 2]]

toArray({ shrimp: 15, tots: 12 }) ➞ [["shrimp", 15], ["tots",12]]

toArray({}) ➞ []


Create a function that takes two numbers as arguments (num, length) and returns an array of multiples of num until the array length reaches length.
Examples :

arrayOfMultiples(7, 5) ➞ [7, 14, 21, 28, 35]

arrayOfMultiples(12, 10) ➞ [12, 24, 36, 48, 60, 72, 84, 96, 108, 120]

arrayOfMultiples(17, 6) ➞ [17, 34, 51, 68, 85, 102]


Create the function that takes an array with objects and returns the sum of people's budgets.

Examples :

getBudgets([
  { name: "John", age: 21, budget: 23000 },
  { name: "Steve",  age: 32, budget: 40000 },
  { name: "Martin",  age: 16, budget: 2700 }
]) ➞ 65700

getBudgets([
  { name: "John",  age: 21, budget: 29000 },
  { name: "Steve",  age: 32, budget: 32000 },
  { name: "Martin",  age: 16, budget: 1600 }
]) ➞ 62600

Create a function that takes an array of objects like { name: "John", notes: [3, 5, 4]} and returns an array of objects like { name: "John", avgNote: 4 }. If a student has no notes (an empty array) then let's assume avgNote: 0.
	Example :

[
  { name: "John", notes: [3, 5, 4]}
] ➞ [
  { name: "John", avgNote: 4 }
]




Create a function that moves all capital letters to the front of a word.
	Examples :

capToFront("hApPy") ➞ "APhpy"

capToFront("moveMENT") ➞ "MENTmove"

capToFront("shOrtCAKE") ➞ "OCAKEshrt"

Count each occurrence of number(can not use predefined function).

			Input: [1,6,3,1,5,9,7,2,1,9,3,7,8,9,10] , no find=7
			Output: 1 present 2 times.
				   2 present 1 times.
				   3 present 2 times.
				   5 present 1 times …….  Etc




Write a function that accepts an array of strings. Return the longest string(can not use predefined function).

		Input: [‘nik’, ’mikhil’, ’Cow’,’Elephant’] 							Output: Elephant

Most Commonly Used two Character in String(can not use predefined function)

				Input: ‘Hii i am ram’
Output; i, a 
Write Program to remove duplicate elements in an array and sort it in descending order(can not use predefined function).

			Input: [5,3,5,2,1,1,7,3,5,6]
			Output: [7,6,5,32,1]

Write a Program to Remove brackets from an algebraic expression(can not use predefined function).

			Input: a + b-(9+c)=3
			Output: a + b- 9+c=3

Write Program to remove duplicate elements in an array and sort it in Accending order(can not use predefined function).

			Input: [Z, A, P, C, A, Z , K, N, C]
			Output: [A, C, K,N, P, Z]
 If subseq's  array  sequence is present in the array, returns true or else returns false.                                                    
Let arr = [5, 7, 3, 2, 2, 7,-1, 5, -3, 13, 4]
Example: 
           Input : Subseq1 = [7, -1, 5, -3] Output:  true
                      Subseq2 = [7, -1, 4, -3]            : false
           Subseq3 = [ -1]                        : true
                      Subseq4 = [13, -3, 4, 1]           : false

Find sum of the Unique numbers: 
Example : Let arr = [1, 2, 2, 1, 3, 5, 1];
 The unique numbers are 1,2, 3, 5 so the sum should be 11.


Difficulty Level : Hard

Create a function that converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized.

Examples :

toCamelCase("A-B-C") ➞ "ABC"

toCamelCase("the-stealth-warrior") ➞ "theStealthWarrior"

toCamelCase("The_Stealth_Warrior") ➞ "TheStealthWarrior"


Create a function that takes an array of strings and returns an array with only the strings that have numbers in them. If there are no strings containing numbers, return an empty array.	

Examples :

numInStr(["1a", "a", "2b", "b"]) ➞ ["1a", "2b"]

numInStr(["abc", "abc10"]) ➞ ["abc10"]

numInStr(["abc", "ab10c", "a10bc", "bcd"]) ➞ ["ab10c", "a10bc"]

numInStr(["this is a test", "test1"]) ➞ ["test1"]




Write a function that takes a list of hours and returns the total weekly salary.
The input list hours is listed sequentially, ordered from Monday to Sunday.
A worker earns $10 an hour for the first 8 hours.
For every overtime hour, he earns $15.
On weekends, the employer pays double the usual rate, regardless how many hours were worked previously that week. For instance, 10 hours worked on a weekday would pay 80+30 = $110, but on a weekend it would pay 160+60 = $220.

Examples :
weeklySalary([8, 8, 8, 8, 8, 0, 0]) ➞ 400
weeklySalary([10, 10, 10, 0, 8, 0, 0]) ➞ 410
weeklySalary([0, 0, 0, 0, 0, 12, 0]) ➞ 280

Create a function which takes in an encoded string and returns an object according to the following example:
Examples :
parseCode("John000Doe000123") ➞ {
firstName: "John",
lastName: "Doe",
id: "123"
}
parseCode("michael0smith004331") ➞ {
firstName: "michael",
lastName: "smith",
id: "4331"
}

parseCode("Thomas00LEE0000043") ➞ {
firstName: "Thomas",
lastName: "LEE",
id: "43"
}
Create a function that takes the current day (e.g. "2022-09-30"), an array of date objects and returns the "current streak" (i.e. number of consecutive days in a row).
Examples :
currentStreak("2022-09-23", [
{"date": "2022-09-18"},
{"date": "2022-09-19"},
{"date": "2022-09-21"},
{"date": "2022-09-22"},
{"date": "2022-09-23"}]) ➞ 3

currentStreak("2022-09-25", [
{"date": "2022-09-16"},
{"date": "2022-09-17"},
{"date": "2022-09-21"},
{"date": "2022-09-22"},
{"date": "2022-09-23"}]) ➞ 0

6. Given a String(Note:- String Will Contain all later from A-Z except 1 letter, that letter you need to find out) :-

Input string=“6 E @ f w 3 x y g N 1 o p Q A b c h i j # K l  d  m  R  T U V  Z”

Output = ‘’S is missing from the String”

Note:- (
Time Complexity:- O(n) means only 1 loop you can use.
without using any predefined function.
)


7.  Given a string s, return the longest 
Palindromic Substring
 
Input: s = "babad"
Output: "bab"
Explanation: "aba" is also a valid answer.

Input: s = "cbbd"
Output: "bb"


8.  Given an unsorted array of integers nums, return the length of    the longest consecutive elements sequence.
You must write an algorithm that runs in O(n) time.
Input: nums = [100,4,200,1,3,2]
Output: 4
Explanation: The longest consecutive elements sequence is [1, 2, 3, 4]. Therefore its length is 4.
Input: nums = [0,3,7,2,5,8,4,6,0,1]
Output: 9

9. Take an array of strings and create a dropdown using array values  the values  of dropdown should be taken dynamically and if we select a value in dropdown and the length of dropdown value is even it should show 1 in console or else if it is odd it should 0.


/* js100 interview problem solving questions * /




https://plainenglish.io/blog/50-javascript-output-questions
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
// Question: What is typeof []
// Answer: Object. Actually Array is derived from Object. If you want to check array use Array.isArray(arr)

// Question: What is typeof arguments
// Answer: Object. arguments are array like but not array. it has length, can access by index but can't push pop, etc.

// Question: What is the value of typeof null
// Answer: "object"

// Question: What is console.log(true+false)
// Answer: 1 here true -->> 1 & false -->> 0 then 1 + 0 -->> 1

// Question: What is 2+true
// Answer: 3. The plus operator between a number and a boolean or two boolean will convert boolean to number. Hence, true converts to 1 and you get result of 2+1

// Question: What is "2"+true
// Answer: 2true here string concatination happer "2"+"true" -->> 2true

// Question: What is the value of -'34'+10
// Answer: -24. minus(-) in front of a string is an unary operator that will convert the string to a number and will make it negative. Hence, -'34' becomes, -34 and then plus (+) will perform simple addition as both the operands are number.

// Question: What is the value of +'dude'
// Answer: NaN. The plus (+) operator in front of a string is an unary operator that will try to convert the string to number. Here, JavaScript will fail to convert the "dude" to a number and will produce NaN.

// Question: If you have var y = 1, x = y = typeof x; What is the value of x?
// Answer: "undefined"

// Question: for var a = (2, 3, 5); what is the value of a?
// Answer: 5. The comma operator evaluates each of its operands (from left to right) and returns the value of the last operand. ref: MDN

// Question: for var a = (1, 5 - 1) * 2 what is the value of a?
// Answer: 8

// Question: What is the value of !'bang'
// Answer: false. ! is NOT.

// Question: What is the value of parseFloat('12.3.4')
// Answer: 12.3

// Question: What is the value of Math.max([2,3,4,5]);
// Answer: NaN

// Question: typeof(NaN)
// Anwser:"number"

// Question:null == undefined
// Answer: true

// Question: If var a = 2, b =3 what would be value of a && b
// Answer: 3

// Question: What is -5%2
// Answer:-1. the result of remainder always get the symbol of first operand
======================================================================================================================================================================
let a = [];
let b = [];
console.log(a==b); //false
console.log(a===b); //false
//Explaination : Here we are comparing memory location, not an array. Memory location of 2 arrays are not same.
--------------------------
let a = [];
let b = a;
console.log(a==b); //true
console.log(a===b); //true
//Explaination : Here we are assigning a to b, where memory location is now same.
---------------------------
let a = [1];
let b = [1];
console.log(a[0]==b[0]); //true
console.log(a[0]===b[0]); //true
//Explaination : Here we are comparing elements inside an array, not a memory location. We specify the index so that's why element get compared.
-----------------------------
let z= [1,2,3]
let a ={name: "priya"}
console.log(...z); // 1 2 3 
//Explaination : ...z means destructing happened i.e, all the elements are come out from an array/object.
------------------------------
console.log(typeof NaN); //number
//Explaination : If we divide "priya"/2 then it will give NaN. 
--------------------------------
let data = 10 - -10;
console.log(data); //20
//Explaination : Minus minus will become plus so 10+10=20
---------------------------------
const set = new Set([1,1,2,2,3,4,5])
console.log(set) //{1,2,3,4,5}
//Explaination : It will remove duplicate values.
---------------------------------
let data ={name: "priya"}
console.log(delete data.name); //true
console.log(data)//{}
//Explaination : delete will return either true or false.
-----------------------------------
let data ={name: "priya"}
console.log(delete data); //false
//Explaination : We can delete the object property only. We can't able to delete the object(i.e, data).
------------------------------------
const data = ["piya", "priya", "supriya"];
const [y] = data;
console.log(y); //"priya"
//Explaination : We are doing destructuring here. y is representing the first index only
-------------------------------------
const data = ["piya", "priya", "supriya"];
const [y,z] = data;
console.log(y,z); //"priya", "priya"
//Explaination : We are doing destructuring here. y is representing the first index only and z representing the second index.
--------------------------------------
const data = ["piya", "priya", "supriya"];
const [,m] = data; // way to access any specific element here at second position
console.log(m); //"priya"
//Explaination : To access any element without taking previous values, we can do just write comma.
--------------------------------------
const data ={name:"priya"}
const {name} = data; //how to get the name property without . dot operator
console.log(name);//priya
//Explaination : Here we did object destructuring.It's not store in continuos memory location but array store in continuoes memory location so that's why we used comma in an array.
--------------------------------------
let data ={name:"priya"}
let data1={city:"ABC"}
data = {...data, ...data1} //merge 2 objects
console.log(data); // {name:"priya", age:"ABC"}
//Explaination : using spread operator we use to merge the 2 objects. Three dots will pop out the property from an object and assign inside curly brackets.
-----------------------------------------
let data ={name:"priya"}
let data1={city:"ABC"}
data = {data, ...data1} //merge 2 objects
console.log(data); // { "data" : {name:"priya"}, "city": "ABC"}
//Explaination :Three dots will pop out the property from an object and assign inside curly brackets. If we didn't do destructing or spread operator then key will be object name(i.e, data) and assign the value as whole object into it.
------------------------------------------
let data ={name:"priya"}
let data1={city:"ABC", name: "supriya"}
data = {...data, ...data1} //merge 2 objects
console.log(data); // { name:"supriya", "city": "ABC"}
//Explaination : If we have same keys while merging then the position of the property will remain same but the value get updated with new value. Because in an objects Keys hould be unique.
-------------------------------------------
const name = "priya"
console.log(name()); //Error: name is not a function
//Explaination : Function we are calling but it's not present so it will an error.
--------------------------------------------
const result = false || {} || 20 || null;
console.log(result); //20
//Explaination : OR operator will find first positive value. Null is a falsy value by default. {} is a positive value. It didn't reach till 20 and null.
--------------------------------------------
const result = null || false || '';
console.log(result); //''
//Explaination : OR operator will find first positive value. It will print '' because any of the true value didn't found so it will pick last value always.
-------------------------------------------
const result = [] || 0 || true;
console.log(result); //[]
//Explaination : OR operator will find first positive value. It will print [] because empty array/object is a positive.
-------------------------------------------------
console.log(Promise.resolve(5)); //Promise {<fulfilled>: 5}
//Explaination : While doing resolve(), itself here a promise. If we pass number/string etc then it will print fulfilled.
------------------------------------------------
console.log("smile" === "smile"); //true
//Explaination : Each emojy contain unicode where we are compairing unicode not the emojy so it's true
-------------------------------------------------
JSON.parse ?
Parse JSON object to a JavaScript value // converting data into js object
-------------------------------------------------
let name  = "priya";
function getName(){
  console.log(name); //Uncaught ReferenceError: Cannot access 'name' before initialization 
  let name = "supriya";
}
getName();
//Explaination : Hoisting used here. If we use VAR the can use variable before declare. But in LET we can't do that. LET/CONST need declaration first then can use it.
--------------------------------------------------
let name  = "priya";
function getName(){
  console.log(name); //Uncaught ReferenceError: Cannot access 'name' before initialization 
  let name = "supriya";
}
getName();
------------------------------------------------------------------------------
let name  = "priya";
function getName(){ 
  let name;
  console.log(name); //undefined
  name = "supriya";
}
getName();
------------------------------------------------------------------------------
let name  = "priya";
function getName(){ 
  let name = "supriya";
  console.log(name); //supriya    
}
getName();
------------------------------------------------------------------------------
let name  = "priya";
function getName(){
  console.log(name); //priya
}
getName();
//Explaination : Let is a block scope.Because of closures we can able to access name which is outside of a function with LET.
--------------------------------------------------
console.log((x => x)('I love')) //"I love"
console.log(`${(x => x)('I love')} to program`) //"I love to program"
//Explaination : Template Literal used here. We use here arrow function which is returning a string 
----------------------------------------------------
function sumValues(x,y,z){
  return x+y+z;
}
sumValues(...[2,3,4]) //how to call a function so that output will be 9
//Explaination : we can't do like this sumValues(2,3,4).
----------------------------------------------------
const name = "priya is a girl.";
console.log(typeof name); //string
console.log(!typeof name); //false //"priya is a good girl" is a string means thruthy value. Nagation of thruthy is falsy value.
console.log(!typeof name === 'object'); //false
console.log(!typeof name === 'string'); //false
console.log(!typeof name === false); //true
//Explaination : We are using negation mark(!) which will return either true or false only.
----------------------------------------------------
const name = "priya";
const age ="10000";
console.log(isNaN(name)); //true
console.log(isNaN(age)); //false
//Explaination : If it's not a number then return True. If it's a number then return false.
-----------------------------------------------------
let person = {name: "priya"};
Object.seal(person); //post seal, how can you modify the person object
person.age ="1000";
person.name ="supriya";
console.log(person); //{name : "supriya"}
//Explaination : Onceyou use Seal we can't able to add the more keys with values into it.But you can modigy the existing key.
-------------------------------------------------------
let data = [2,9,0,10];
data.shift();//remove first element
console.log(data); //[9,0,10]
data.pop(); //remove last element
console.log(data);//[9,0]
//Explaination : shift and pop use to remove the elements from first and last index.
--------------------------------------------------------
//check the value is even or odd
let a =10;
console.log(a%2===0 ? true : false); //true
//Explaination : Need to divide by 2 and then checking if reminder is zero/one.
----------------------------------------------------------
let data ={ name : "priya"};
delete data.name;
console.log(data); //{}
//Explaination : delete always work with object properties not a object itself.
---------------------------------------------------------
let data ="true";
//convert data into boolean false value
console.log(!data); //false
console.log(typeof !data); //boolean
//Explaination : ! will make boolean value(or opposite value). 
---------------------------------------------------------
let data ="true";
//convert data into boolean true value
console.log(!!data); //true
console.log(typeof !!data); //boolean
//Explaination : ! will make boolean value(or opposite value). 
---------------------------------------------------------
Diff between Map and foreach: Map will return new thing but Foreach didn't return anything.
---------------------------------------------------------
let data = ["piya", "priya", "supriya"];
delete data[1];
console.log(data); //["piya",,"supriya"] //["piya",empty,"supriya"]
console.log(data.length); //3
//Explaination : Whenever element deleted from an object it will create a empty space. Array length will always reain same.
-------------------------------------------------------------
//merge 2 arrays
const a =[1,2,3];
const b =[4,5,6];
const c =[...a, ...b]
console.log(c); //[1,2,3,4,5,6]
//Explaination : using spread operator
----------------------------------------------------------------
const a =[1,2,3];
const b =[3,4,5,6];
const c =[...a, ...b]
console.log(c); //[1,2,3,3,4,5,6]
//Explaination : using spread operator still we can merge and both values will be present in arrays. But in an object, it will take the lates value and assigned to the 1st position of that key.
-------------------------------------------------------------------
let c = 3**3;
console.log(c); //27
console.log(3*3); //9
//Explaination : 3 square 3 means 3*3*3
---------------------------------------------------------------------
let a=2;
setTimeout(()=>{
  console.log(a); //100
},0)
a=100;
//Explaination : Here we are using zero time interval. setTimeout is async function so it will execute at last. Firstly all the sync code will get execute. so that's why 100 is assigned to a.
------------------------------------------------------------------------
let a =2;
let A =30;
console.log(A); //30
//Explaination : a and A both are diff variables.
------------------------------------------------------------------------
let A10="hello";
let 10A ="hi";
console.log(A10); //hello
//console.log(10A); //error
//Explaination : Variable can't start with a number.
------------------------------------------------------------------------
let a="hello";
let b =`hello`;
console.log(a === b); //true
console.log(a == b); //true
//Explaination : Doble code and backticks both are same.
--------------------------------------------------------------------------
let a =1;
let c =2;
console.log(--c === a); //true
//Explaination : --c will be 1 so thats why true.
--------------------------------------------------------------------------
let a =1;
let b =1;
let c =2;
console.log(a === b === -c); //false
//Explaination : a===b gives True. true === -c(number) gives false.
---------------------------------------------------------------------------
console.log(3*3); //9
console.log(3**3); //27
//console.log(3***3); //error
//Explaination : *** doesn't exist in js.
----------------------------------------------------------------------------
console.log(a); //undefined
var a;
//Explaination : We can use VAR variable before its declaration. We didn't assign any value but still by default "undefined" will be store in it.undefined means declared but value didn't initialised.
-----------------------------------------------------------------------------
console.log(a); //not defined
//Explaination : Not defined means variable didn't even declared.Also value is not assogned.
-----------------------------------------------------------------------------
console.log([[[]]]); //[[[]]]
//Explaination : It will print the nested array. We will get 3 nested array and each one have 1 element but at the last array will be empty.
------------------------------------------------------------------------------
How to find Operating system name?
navigator.plateform we can use it. //win32
-------------------------------------------------------------------------------
let for = 100; //Error
//Explaination : For is a reserved keyword.
-------------------------------------------------------------------------------
function fruit(){
  console.log(name); //undefined
  console.log(price); //Error
  var name = "priya";
  let price = 1000;
}
fruit()
//Explaination : Hoisting concept used here. Error because in LET declaration first then only we can use it. but in var we can use brfore its declaration.
-------------------------------------------------------------------------------
for(var i=0; i<3; i++){ //i=0 //1 //2 //3
  setTimeout(()=>console.log(i),1) // 3,3,3
}
//Explaination : Var is a global variable. Firstly Sync code get executed then async code will start to execute. so i value incremented from 0 to 3 when pointer reaches to setTimeout so it will print 3 thrice time.
---------------------------------------------------
for(let i=0; i<3; i++){ //i=0 //1 //2 //3
  setTimeout(()=>console.log(i),1) //0 //1 //2
}
//Explaination : LET is a block scope. so it will print 0,1,2. Its having own islocated scope.
----------------------------------------------------
console.log(+true); //1
console.log(typeof +true); //number
//Explaination : if we write + in front of anything then it will convert into a number.
----------------------------------------------------
console.log(!"priya"); //false
console.log(typeof ("priya")); //string
//Explaination : ! will give either true/false.! means false and !! means true.
----------------------------------------------------
let data = "size";
const bird = {size : "small"}
console.log(bird[data]); //small
console.log(bird["size"]); //small
console.log(bird.size); //small
console.log(bird.data); //undefined
//Explaination : If we wants to access variable with object then use [] notation(. notation will not work).
------------------------------------------------------
let c = {name  : "priya"};
let d;
d=c;
c.name = "supriya";
console.log(d.name); //supriya
//Explaination : Using assignment operator we are accessing the same memory allocation. 
-------------------------------------------------------
var x;
var x=10;
console.log(x); //10
//Explaination : Can be declare multiple times.
---------------------------------------------------------
var x;
let x=10;
console.log(x); //Error
//Explaination : Can't be declare multiple times with LET.
----------------------------------------------------------
let a = 3;
let b = new Number(3);
console.log(a == b); //true
console.log(a === b); //false
console.log(typeof b); //object
//Explaination : === will give false because a will give number but b will give an object.
-------------------------------------------------------
let name;
nmae ={}; //wrong variable name i wrote
console.log(name); //undefined
//Explaination : by default it wil be undefined if we declare first.
---------------------------------------------------------
function first(){
  console.log("Woof!!"); //Woof!!
}
first.name = "apple";
first();
//Explaination : To add the property with a function then it will not create a impact.
----------------------------------------------------------
function sum(a,b){
  return a+b;
}
console.log(sum(1, "2")); //12
//Explaination : 2 is passed as a string so it will get concat. num+string = string
------------------------------------------------------------
let num = 0;
console.log(num++); //0
console.log(++num); //2
console.log(num); //2
//Explaination : ++ will increase the value by 1. preincrement and postincrement used here.
--------------------------------------------------------------
function getAge(...args){ //[1000]
  console.log(typeof args); //object
}
getAge(1000);
//Explaination : typeof args means typeof an array means typeof [] is object.
--------------------------------------------------------------
function getAge(){ 
 age = 1000;
 console.log(age); //1000
}
getAge();
//Explaination : if we didn't declare with Var/Let/const then by default it will become as a Var.
------------------------------------------------------------------
function getAge(){ 
  'use strict'
 age = 1000;
 console.log(age); //error
}
getAge();
//Explaination : Use strict wil give a error because it forces to use a proper way of the variable declaration.
----------------------------------------------------------------------
const sum = eval('10*10+5');
console.log(sum); //105
//Explaination : It will perform the numerical operation
----------------------------------------------------------------------------
const obj = {1:"a", 2:"b"}
console.log(obj.hasOwnProperty("1")); //true
console.log(obj.hasOwnProperty(1)); //true
//Explaination : "1" and 1 treat as same.
----------------------------------------------------------------------------
const obj = {a:"one", b: "two", a:"three"}
console.log(obj); // {a:"three", b: "two"}
//Explaination : Key position will be same but tha value get updated with new value in object.
----------------------------------------------------------------------------
for(let i=1; i<5; i++){
  if(i==3) continue;
  console.log(i); //1,2,4
}
//Explaination : If i =3 then it will not execute the code for 3, but can execute for i=4.
------------------------------------------------------------------------------
const foo = () => console.log("first");
const bar = () => setTimeout(()=> console.log("second"));
const baz = () => console.log("third");
bar();
foo();
baz();
//Explaination : first,third, second. Because asyn operation work post all the syn operation get complete.
----------------------------------------------------------------------------
<div onClick="console.log("first div")">
  <div onClick="console.log("second div")">
    <button onClick="console.log("button")">
     Click Me
     </button>
  </div>
</div>
//Explaination : button, second div, first div. Even bubbling happened here.
---------------------------------------------------------------------------
const person = {name:'priya'};
function sayHi(age){
  return `${this.name} is ${age}`;
}
console.log(sayHi.call(person,21)); //"priya is 21"
console.log(sayHi.bind(person,21)); //it will return a function. //function sayHi(age){  return `${this.name} is ${age}`;}
console.log(sayHi.bind(person,21)()); //"priya is 21"
//Explaination : Bind will always return a function so require to invoke the function.
------------------------------------------------------------------------------
function sayHi(){
  return (()=>0)();
}
console.log(typeof sayHi()); //number
//Explaination : sayHi will return anonymous arrow function/IIFE, where it will return 0. type of 0 is number.
----------------------------------------------------------------------------
function sayHi(){
  return ()=>0;
}
console.log(typeof sayHi()); //function
console.log(typeof sayHi()()); //function
//Explaination : sayHi will return anonymous arrow function/IIFE, where we didn't invole the arroe function so it will return function.
-----------------------------------------------------------------------------
console.log(typeof typeof 1); //string
//Explaination : typeof 1 is a number and typeof number is a string.
-----------------------------------------------------------------------------
const numbers = [1,2,3];
numbers[6]=11;
console.log(numbers); //[1,2,3,,,,11]
//Explaination : Array store elements in a continuous memory location. It will give empty in between an array.
-------------------------------------------------------------------------------
const numbers = [1,2,3];
numbers[9]=numbers;
console.log(numbers); //[1,2,3,,,,.......]
//Explaination: It will print infinite loop.
-------------------------------------------------------------------------------
console.log(!!null); //false
console.log(!!""); //false
console.log(!!1); //true
//Explaination: !null give true and !!null give false. !1 give false and then !!1 give true.
-------------------------------------------------------------------------------
console.log(setInterval(()=>console.log('Hi'), 1000));
console.log(setInterval(()=>console.log('Hi'), 1000));
console.log(setInterval(()=>console.log('Hi'), 1000));
//Explaination: setInterval will give uniques id to stop. It will give like 1,2,3. so it will print 1,2,3,Hi,Hi, Hi, Hi, Hi, .....so on.
------------------------------------------------------------------------------
console.log(setTimeout(()=>console.log('Hi'), 1000));
console.log(setTimeout(()=>console.log('Hi'), 1000));
console.log(setTimeout(()=>console.log('Hi'), 1000));
//Explaination : it will print 1,2,3,Hi,Hi, Hi.
-------------------------------------------------------------------------------
console.log([..."priya"]); //["p","r","i","y","a"]
//Explaination: It will convert into an array.
-------------------------------------------------------------------------------
const firstPromise = new Promise((res, rej)=>{
  setTimeout(res, 500, 'one');
})
const secondPromise = new Promise((res, rej)=>{
  setTimeout(res, 100, 'second');
})
Promise.race([firstPromise, secondPromise]).then(res => console.log(res));
//Explaination: Race will return only first matching result so it will print 100. For 500 it will take time to execute so it will not get print.
-----------------------------------------------------------------------------------
let person = {name: "priya"};
const numbers = [person];
person = null;
console.log(numbers, person); // [{name : "priya"}] //null
//Explaination: We try to empty the objecti,e person, but still an array i.e, numbers conatin value so it will not create an impact while assigning null to person.
----------------------------------------------------------------------------------
const person = {name: "priya", age: 1000};
for(const item in person){
  console.log(item); //name, age
}
//Explaination: For in loop give a keys only.
--------------------------------------------------------------------------------------
let data = 3+4+'5';
console.log(data); //"75"
console.log(typeof data); //string
//Explaination: It will add as a string.
------------------------------------------------------------------------------------------
console.log(typeof 3+4+'5'); //"number45"
//Explaination: operation went from left to right side.
----------------------------------------------------------------------------------------
console.log(typeof (3+4+'5')); //"75" //string
console.log(typeof (3+4+  +'5'));//number
//Explaination: To find out the typeof when the all the operation get complete thrn have to enclose in paranethisis. If we add + plus sign to any string it will convert to a number.
----------------------------------------------------------------------------------------
let data = [1,2,3].map( num =>{
  if (typeof num === 'number') return;
  return num*2;
})
console.log(data); //[undefined,undefined,undefined]
//Explaination: If jusr return then it will print undefined.
----------------------------------------------------------------------------------------
function getInfo(member){
  member.name = "priya";
}
const person = {name : "supriya"}
getInfo(person);
console.log(person); //{"name":"priya"}
//Explaination: If we pass an object as argument it will have call by refrence, means having same memory location.
----------------------------------------------------------------------------------------
function Car(){
  this.make = "tata";
  return {make: "kia"};
}
const myCar = new Car();
console.log(myCar.make); //kia
//Explaination: return will overrite the property.If we didn't return then it will print tata.
----------------------------------------------------------------------------------------
(()=>{
  let x = (y = 10);
})()
console.log(typeof x, y); //"undefined" //10
//Explaination: x is a block scope, and we are trying to console x outside of x so that's why undefined.
-----------------------------------------------------------------------------------------
(()=>{
  let x = y = 10;
})()
console.log(typeof y); //number
//Explaination: x is a block scope, and y is a var because y is not declared so by default it will be var.
----------------------------------------------------------------------------------------
(()=>{
  let x = 10;
})();
(()=>{
  let x = 10;
})();
console.log(typeof x); //undefined
//Explaination: x is a block scope.
---------------------------------------------------------------------------------------
(()=>{
  let x = y = 10;
})();
(()=>{
  let x = y = 20;
})();
console.log(y); //20
//Explaination: y is a var scope so it will overrite from 10 to 20
-----------------------------------------------------------------------------------------
let x =100;
(()=>{
  var x = 10;
})();
console.log(x); //100
//Explaination: x=10 contain inside a block because we already declare with 100 outside so it will print 100.
-------------------------------------------------------------------------------------------
const func = (function(a){
                   delete a;
                   return a;
               } )(5)
console.log(func);

output: 5
//delete keyword only use with object properties. here a is a variable so it will not work the variable. //delete user.age 
------------------------------------------------------------------------------------------
Dynamic property of object :
const property = "firstName";
const name = "Priya";

const user = {
  property : name //{"property" : "Priya"}
}
console.log(user);

const user1 = {
  [property] : name //dynamic property required [] //{"firstName" : "Priya"}
}
console.log(user1);
------------------------------------------------------------------------------------------
const user ={
  name : "priya",
  age : 100
}

//iterate through keys
for(let item in user){
  console.log(item) //name age
}
//iterate through values
for(let item in user){
  console.log(user[item]) //priya 100
}
------------------------------------------------------------------------------------------
const user ={
  name : "priya",
  age : 100
}

//double the age as 200 //iterate through keys
for(let item in user){
 if(typeof user[item] === "number"){
   user[item]*=2
 }
}

console.log(user)
------------------------------------------------------------------------------------------
const a = {}
const b = {key : "b"}
const c = {key : "c"}

a[b] = 123;
a[c] = 456;
console.log(a[b]); //456

//console.log(a) //{"[object Object]" : 456}
//here object is not converted into a string so printing key as object Object.
//so for both it will be 
//a["[object Object]"] = 123;
//a["[object Object]"] = 456;
//it get override by 456.
------------------------------------------------------------------------------------------
const user = {
  name :"priya",
  age : 100
}
//convert into a string
const str = JSON.stringify(user)
console.log(str)//{'name':'priya','age':100}"

//convert string onto an object
console.log(JSON.parse(str)) //{ name : "priya, "age":100}


*****************
Real Usecases : Storing in local storage. We can't store the object as a value so require to convert into a string.
const user = {
  name :"priya",
  age : 100
}
console.log(JSON.stringify(user)) //convert into a string
console.log(JSON.parse(JSON.stringify(user)))  //convert into an object

localStorage.setItem("testAsKey", JSON.stringify(user)) {"name":"priya","age":100}
localStorage.setItem("testAsKey", user) //[object Object] beacuse we are forcefully trying to convert in a string

JSON.parse(localStorage.getItem("testAsKey")) //will get as a object
------------------------------------------------------------------------------------------
const user = {
  name :"priya",
  age : 100
}
console.log(JSON.stringify(user,["name"])) //"{'name':'priya'}"

//wheen we pass as a array then it will convernt only those properties and ignore rest of the proerties
------------------------------------------------------------------------------------------
const shape = {
  radius : 10,
  diameter(){
    return this.radius*2; //this pointing to shape
  }
 parimeter : () => 2*Math.PI*this.radius; //this pointing to window where it's not exist
}
console.log(shape.diameter()) //20
//console.log(shape.parimeter()) //Nan
-------------------------------------------------------------------------------------------
let user = {
  name : "Priya",
  age : 100
}

const name = "Supriya";
//const {name} = user; //Identifier 'name' has already been declared 
const {name : myName} = user;

console.log(myName) //Priya
-------------------------------------------------------------------------------------------
let user = {
  age : 100,
  fullName : {
    first : "Priya",
    last : "Bagde"
  }
}

const {fullName : {first}} = user;
console.log(first); //"Priya"
//Destructuring at deep nested
-------------------------------------------------------------------------------------------
let c = {greeting : "Hey!"}
let d;

d=c;
c.greeting = "Hello"
console.log(d.greeting); //Hello
//We are passing the refrence not the propertues of an object so when we changge the roperty of any object it will reflect in both objects
-------------------------------------------------------------------------------------------
let person = {name : "priya"}
const members = [person]
person = null
console.log(members);// [{"name":"priya"}]

let person = {name : "priya"}
const members = [person]
person.name = null
console.log(members);// [{"name":null}]
//because we are modifying the property of object
-------------------------------------------------------------------------------------------
Ways to make deep copy:
1. object.assign
2. {...obj}
3. JSON.parse(JSON.stringyfy(obj))
-------------------------------------------------------------------------------------------
console.log(1);

function print(name){
  setTimeout(()=>{
    return `${name}`
  },1000)
}
let value = print("Priya");
console.log(value)

console.log(2);
Reason : It run the code quickly and it will not wait for setTimeout so value will be undefined
---------------------------------------------------
Above code can be fix by callback:
console.log(1);
function print(name, cb){
  setTimeout(()=>{
     cb(`${name}`)
  },1000)
}
print("Priya", (value)=>{
  console.log(value)
});
console.log(2);
-------------------------------------------------------------------------------------------
let promises = new Promise((resolve, reject)=>{
  setTimeout(()=>{
    let state = true;
    if(state){
      resolve("Resolved Promises!!...");
    }else{
      reject("Rejected Promises!!...");
    }  
  }, 1000)
})
promises.then((res)=>console.log(res))
.catch((err)=>console.log(err))
//resoled!!....
-------------------------------------------------------------------------------------------
console.log(1);

const data = new Promise((resolve, reject)=>{
  console.log(2);
  resolve(3);
})

data.then((res)=>{
  console.log(res)
})

console.log(4); //1 2 4 3
-------------------------------------------------------------------------------------------
console.log(1);

const data = new Promise((resolve, reject)=>{
  console.log(2);
  //resolve(3);
})

data.then((res)=>{
  console.log(res)
})

console.log(4); //1 2 4 
If we are not returning anything it will not print anything .
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
let a = "true";
setTimeout(()=>{
  a=false;
}, 2000)

while(a){
  console.log("1")
} 

Reason: 1, 1, 1,...... 
Explanation: Event loop will add setTimeout callback in Macrotask queue and will push it to call stack for execution only when the main thread finishes executing.

Here, since 'a' is true and isn't being set to false anywhere in main thread, the while loop will run infinitely, and setTimeout callback will never get a chance to run.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
function run(value, time){
  return new Promise((resolve)=>{
    setTimeout(()=>{
      resolve(value)
    }, time)
  })
}
async function task(){
  let a = await run(1, 1000); //1value //1 sec
  let b = run(2, 2000); //2value //2 sec
  let c = run(3, 1000);  //3value //execute before b so will not take extra time
  console.log(a + await b+ await c);
}
task()

6 'in 3Sec'

Explanation: In line 10, a setTimeout() timer of 1 sec will be triggered and due to 'await', it will wait for the timer to expire, and after 1 sec, value of a is 1. 

Then since there is no 'await' in line 11 and 12, the 2 timers of 2 sec and 1 sec will be triggered simultaneously. Then in line 14, since b hasn't been resolved, due to await, it will wait for another 2 sec, and since the 2 timers started simultaneously, the other 1 sec timer would already have expired. 

So, after another 2 sec, value of b will be 2, and then immediately after that, value of c will be 3. 

👉 Output : 1 + 2 + 3 = 6
👉 Total time: 1 (line 10) + 2 (await b, in line 14) + 0 (await c, in line 14) = 3 sec
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
const fetchData = function(){
  return new Promise((res, reject)=>{
    reject("Error!!")
  })
}

fetchData()
.then(null, (err)=>{
  console.log("First");
  console.log(err);
})
.catch(()=>{
  console.log("Second");
  console.log(err)
})

Explaination : "First" "Error!!"
reject("Error!!") gives string value so it will go to THEN block rather than CATCH block.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
displayName();
var displayName = function(){
  console.log("Priya")
} 
function displayName(){
  console.log("dolly")
}
displayName();

//Explaination : dolly priya

Normal function will get execute before, because of function Hoisting concept, then function expression wil get execute.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
const inc = async(x) => {
  x = x + await 1; //2
  return x;
}

const increment = async(x) =>{ 
  x = x+1; //2+1
  return x; //3
}
inc(1)
.then((x)=>{ //2
  increment(x) //2
  .then((x)=>console.log(x)) //3
})
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
const p1 = Promise.resolve("First");
const p2 = Promise.reject("Second");
const p3 = Promise.resolve("Third");
const runPromise = async() =>{
  try{
    const res = await Promise.all([p1,p2,p3]);
    console.log(res);
  }
  catch(err){
    console.log(err)
  }
}
runPromise();

//output : Second

Promise.all() returns array of resolved promises values and if either any of the promise is rejected, then it directly returns the rejected promise value through catch block.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
console.log("start");

async function getData(){
  console.log("priya");
  return "Dolly";
}

getData()
.then((res)=> console.log(res));

console.log("end");
//start priya end Dolly
//all the console will print first then aync and setTimeout
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
const promise = () => Promise.resolve("Success");
function first(){
  promise().then((res)=> console.log(res)); //async
  console.log("First"); //sync
}
async function second(){
  const res = await promise(); 
  console.log(res); //async
  console.log("Second"); //sync
}
first();
second();

// First Sucess success second
// sync(console) run hen async(promise)
//await pause the line of execution
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
const person1 = {
  name : "Priya"
}
const person2 = {
  name : "Dolly"
}
const person = Object.assign(person1, person2);

console.log(person); //{"name" : "Dolly"}
console.log(person.name); //Dolly
console.log(person1.name); //Dolly
console.log(person2.name); //Dolly

//Having same key name so, the value is override and it will be "Dolly"

Explanation : As Object.assign() method will add all the key values of person2 to person1 and return the reference of person1 to person and if same key are there they'll be overwritten.
Basically person1 and person are referring to same object.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
const calc=(a)=>{
  return (b)=>{
    if(b) return calc(a+b);
    return a;
  }
}
console.log(calc(1)(2)(3)(4)()) //10 currying
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
const fetchData = function(){
  return new Promise((res)=> res("One"));
}
let isLoading = true;
fetchData()
.then((result)=>{
  console.log(result);
})
.finally(()=>{
         console.log("Two");
          isLoading = false;
})      
console.log(isLoading)  

//true one two
//console value run first
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

const person = {
  name : "Priya",
  displayName(){
    console.log(this.name) //pointing to the person object
  }
}

const jayesh = Object.create(person)
person.displayName(); //Priya
console.log(jayesh); //{}
jayesh.displayName(); //Priya
I believe Object.create() creates a new object from the existing object, and both have the same memory addresses.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
let p = new Promise((resolve, reject)=>{
   reject(Error("Failed!!"))                    
})

p.catch((error)=>{
  console.log(error); //{}
  console.log(error.message); //failed
}).then((result)=>{
  console.log(result) //undefined //doesn't return anything
})

//Failed!! undefined
Explanation: In line 2, we are rejecting the promise 'p' with the argument as Error("Fails!"), which is an 'Error' object with property 'message' set to 'Fails!'. So, in line 5, the error callback passed to catch() method of promise 'p' receives the above passed Error object as the 'error' parameter, and so 'error.message' (Fails!) is printed. 

Now, as this catch handler is not returning any value so, the chained 'then' handler will be called with undefined as parameter.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
/* 💡"JavaScript-with-JC" - Guess the Output? */

// 👉 MCQ-1
function MCQ1() {
  const person = {
    name: "Jayesh",
    displayName1: function () {
      console.log("name1", this.name);
    },
    displayName2: () => {
      console.log("name2", this.name);
    },
  };
  person.displayName1();
  person.displayName2();

  // 👍A) name1 Jayesh , name2 Jayesh
  // 💡B) name1 Jayesh , name2 undefined
  // 💖C) name1 Jayesh , name2
  // 😀D) name1 , name2 Jayesh

  /* 
  In window browser answer is C) name1 Jayesh , name2 because arrow function inherits "this" from its outer function where "this" is window.
  and window has by default property name that is used for setting or returning the name of a window and in above case window.name is empty string.
  
  In other compilers answer is B) name1 Jayesh , name2 undefined because arrow function inherits "this" from its outer function where "this" refers to global object.
  */
}
// MCQ1();

// 👉 MCQ-2
function MCQ2() {
  let name = "Jayesh";
  function printName() {
    if (name === "Jayesh") {
      let name = "JC";
      console.log(name);
    }
    console.log(name);
  }
  printName();

  // 👍A) Jayesh     💡B) Jayesh, JC
  // 💖C) JC, JC     😀D) JC, Jayesh

  /* Answer is D) JC, Jayesh because let variables are block scope, name inside if condition will shadow outer name*/
}
// MCQ2();

// 👉 MCQ-3
function MCQ3() {
  var player = "Virat";
  function displayPlayer() {
    if (player === "Virat") {
      var player = "VK";
      console.log(player);
    }
    console.log(player);
  }
  displayPlayer();

  // 👍A) VK, Virat    💡B) VK, VK
  // 💖C) undefined    😀D) VK, undefined

  /* 
   Answer is C) undefined because var variables are functional scope, When displayPlayer fn starts executing, Execution context of
   displayPlayer will be created in callstack and at the memory creation phase var variable player is initialized as undefined. 
   hence if condition will become false and It will print only undefined.
  */
}
// MCQ3();

// 👉 MCQ-4
function MCQ4() {
  const person = {
    name: "Jayesh",
    age: 24,
  };

  const getAge = person.age;
  delete person.age;

  console.log(person);
  console.log(getAge);

  // 👍A) { name: 'Jayesh', age: 24 }, null
  // 💡B) { name: 'Jayesh' }, 24
  // 💖C) { name: 'Jayesh' }, undefined
  // 😀D) { name: 'Jayesh', age: 24 }, 24

  /*
  Answer is B) { name: 'Jayesh' }, 24 because delete keyword deletes property of an object and we are setting getAge as pass by value.
 */
}
// MCQ4();

// 👉 MCQ-5
function MCQ5() {
  // No Strict Mode
  name = "Jayesh"; // window.name ( property of window object )
  console.log(delete name);

  const displayName = (function (name) {
    console.log(delete name); // Local variable of function
    return name;
  })("JC");

  console.log(displayName);

  // 👍A) true, false, JC
  // 💡B) true, true, undefined
  // 💖C) false, false, JC
  // 😀D) false, true, undefined

  /*
  Answer is A) true, false, JC because delete keyword deletes only property of an object. 
  delete keyword can not delete local variables ( declared with var, let, and const ) and functions. 
  delete keyword can delete global variables as they are property of window object.
 */
}
// MCQ5();

// 👉 MCQ-6
function MCQ6() {
  const arr = [];

  for (var i = 0; i < 5; i++) {
    arr[i] = function () {
      return i;
    };
  }

  console.log(arr[0]());
  console.log(arr[4]());

  // 👍A) 0, 4     💡B) 4, 4
  // 💖C) 5, 5     😀D) TypeError

  /*
  Answer is C) 5, 5 because variables declared with var keyword are function-scoped or globally-scoped but not blocked scoped. 
  Inner function will form the closure and points to the updated value of i that is 5. 
  In the case of Let variable, as they are blocked scoped so inner function will hold different values of i from 0 to 4.
 */

  /* 👇 In the case of Let variable */
  const arrBlock = [];

  for (let i = 0; i < 5; i++) {
    arrBlock[i] = function () {
      return i;
    };
  }

  console.log(arrBlock[0]()); // 0
  console.log(arrBlock[4]()); // 4
}
// MCQ6();

// 👉 MCQ-7
function MCQ7() {
  let person = { name: "Jayesh" };
  const personArray = [person];
  person = null;
  console.log(personArray);

  personArray = [];
  console.log(personArray);

  // 👍A) [ { name: "Jayesh" } ], []
  // 💡B) [ { name: "Jayesh" } ] , TyperError
  // 💖C) [ null ], TypeError
  // 😀D) [ {} ], []

  /*
  Answer is B) [ { name: "Jayesh" } ] , TyperError because person = null will only disconnect the person variable from value { name: "Jayesh"} which is stored in memory, personArray[0] will still point to same value { name: "Jayesh"}.
  and personArray = [] at this line TyperError as const variable can't be redeclared and throws Uncaught TypeError: Assignment to constant variable.  
 */
}
// MCQ7();

// 👉 MCQ-8
function MCQ8() {
  const value = { number: 10 };

  const addition = (x = { ...value }) => {
    console.log((x.number += 5));
  };

  addition();
  addition();
  addition(value);
  addition(value);

  // 👍A) 15, 20, 25, 30    💡B) 15, 15, 20, 25
  // 💖C) 15, 15, 15, 15    😀D) 15, 15, 15, 20

  /*
  Answer is D) 15, 15, 15, 20 because when we call addition function 3rd time with passing value object as an argument, then x will take value as pass by reference and will update number property of original object ( value in this case ) to 15.  
  Hence, while calling addition function 4th time will console 15 + 5 => 20.
 */
}
// MCQ8();

// 👉 MCQ-9
function MCQ9() {
  function makePerson() {
    return {
      userName: "Jayesh",
      ref: this,
    };
  }

  const person = makePerson();
  console.log(person.ref.userName);

  // 👍A) Jayesh      💡B) ""
  // 💖C) undefined   😀D) TypeError

  /*
  Answer is C) undefined because "this" keyword in makePerson function will refer to the window object,
  person.ref.userName is same as Window.userName and no property named with userName is present in window object, Hence It will console undefined.
 */

  // 👇 We can get "Jayesh" as an output by doing small change in above question :-
  function makePerson2() {
    return {
      userName: "Jayesh",
      // 👇 Here, We have assigned a function to ref property of an object, and function's "this" will point to the returned object.
      ref: function () {
        return this;
      },
    };
  }

  const person2 = makePerson2();
  console.log(person2.ref().userName); // Jayesh
}
// MCQ9();

// 👉 MCQ-10
function MCQ10() {
  const user = {
    userName: "Jayesh",
    displayName: function () {
      console.log(this.userName);
    },
  };

  setTimeout(user.displayName, 1000);

  // 👍A) Jayesh     💡B) undefined
  // 💖C) ""         😀D) TypeError

  /*
  Answer is B) undefined because setTimeout is using user.displayName as a callback function rather than object method.
  callback function's "this" will refer to the window object and It will console undefined as there is no property such as userName in the window object.   
  */

  // 👇 We can get "Jayesh" as an output by wrapping the user.displayName() inside a function :-

  setTimeout(function () {
    user.displayName(); // Here, displayName is called by user object ( object method ). Hence, "this" will refer to user object.
  }, 1000);
}
// MCQ10();

// 👉 MCQ-11
function MCQ11() {
  const series = { name: "JavaScript-with-JC" };

  function getSatus(postNumber) {
    return `${this.name} 🌟 ${postNumber}`;
  }

  console.log(getSatus.call(series, 50));
  console.log(getSatus.bind(series, 50));

  // 👍A) JavaScript-with-JC 🌟 50, undefined
  // 💡B) JavaScript-with-JC 🌟 50, JavaScript-with-JC 🌟 50
  // 💖C) JavaScript-with-JC 🌟 50, [Function: bound getSatus]
  // 😀D) JavaScript-with-JC 🌟 50, TypeError

  /*
  Answer is C) JavaScript-with-JC 🌟 50, [Function: bound getSatus] because call, apply and bind methods are used for function borrowing in JavaScript.   
  The call method immediately invokes the borrowed function where as bind method does not invoke the borrowed function immediately, bind method returns a copy of borrowed function
  that can be called later on with or without passing new arguments to it.
  */

  // 👇 We can get 'JavaScript-with-JC 🌟 50, JavaScript-with-JC 🌟 50' as an output by calling borrowed function of bind method :-

  console.log(getSatus.call(series, 50)); // JavaScript-with-JC 🌟 50
  console.log(getSatus.bind(series, 50)()); // JavaScript-with-JC 🌟 50
}
// MCQ11();

// 👉 MCQ-12
function MCQ12() {
  var name = "Jayesh";

  function displayName() {
    console.log(this.name);
  }

  const person = {
    name: "JC",
    method(fn) {
      fn();
    },
  };

  person.method(displayName);

  // 👍A) JC           💡B) Jayesh
  // 💖C) undefined    😀D) TypeError

  /*
  Answer is B) Jayesh because displayName function is passed to person object method as a callback function.
  "this" keyword in displayName function will refer to window object and window object has a property "name" with value "Jayesh". Hence, It will console Jayesh as an output.
  */

  // 👇 We can get JC as an output by attaching call method with fn() inside person method :-

  const person2 = {
    name: "JC",
    method(fn) {
      fn.call(this); // borrowing function and passing "this" of person2 object.
    },
  };

  person2.method(displayName); // JC
}
// MCQ12();

// 👉 MCQ-13
function MCQ13() {
  var length = 4;

  function callback() {
    console.log(this.length);
  }

  const object = {
    length: 5,
    method: function () {
      arguments[0]();
    },
  };

  object.method(callback, 2, 3);

  // 👍A) 2     💡B) 3
  // 💖C) 4     😀D) 5

  /*
  Answer is B) 3 because arguments keyword is an array of arguments passed to the function. 
  Here while calling object.method(), we are passing three arguments callback fn(), 2 and 3.
  If we try to console arguments it will look like this 👇

  Arguments(3) [ƒ, 2, 3, callee: ƒ, Symbol(Symbol.iterator): ƒ]
  0: ƒ callback()
  1: 2
  2: 3
  callee: ƒ ()
  length: 3
  Symbol(Symbol.iterator): ƒ values()
  [[Prototype]]: Object

  As we can clearly see, arguments is having length property that is equal to number of arguments passed to function.
  So, arguments[0] is nothing but the first argument passed to function that is callback function in this case.
  As we know, Everything in JavaScript is an object ( arguments is also an object which has length property with value 3 )
  arguments[0]() function's "this" will refer to arguments object. Hence, It will console 3 as an output.
  */
}
// MCQ13();

// 👉 MCQ-14
function MCQ14() {
  var name = "Jayesh";

  function displayName() {
    console.log(this.name);
  }

  const person = {
    name: "JC",
    method: displayName.bind(this),
  };

  person.method();

  // 👍A) Jayesh       💡B) JC
  // 💖C) undefined    😀D) TypeError

  /*
  Answer is A) Jayesh because "this" inside the definition for person object does not refer to person object. 
  "this" will refer to the window object here, and binding displayName function with passing window's this  
  as a context will return a copy of bound function that is stored in method property of person object. 
  So, While calling person.method() will console Jayesh as an output.
  */

  // 👇 We can get JC as an output by wrapping displayName.bind(this) inside a function because "this" inside the normal function of an object refers to the object :-

  const person2 = {
    name: "JC",
    method: function () {
      return displayName.bind(this); // Here, "this" refers to the person2 object
    },
  };

  person2.method()(); // JC
}
// MCQ14();

// 👉 MCQ-15
function MCQ15() {
  function show() {
    console.log(this.name);
  }

  const person1 = { name: "Jc" };
  const person2 = { name: "Jayesh" };

  show = show.bind(person1).bind(person2);
  show();

  // 👍A) Jayesh       💡B) undefined
  // 💖C) JC           😀D) TypeError

  /*
  Answer is C) JC because a function which is bound with bind keyword can not be re-bound with other new context, bind chaining does not exist.
  once the function is bound to a particular object, It will always be bound to that object no matter how many times it's further bounded.
  */
}
// MCQ15();

// 👉 MCQ-16
function MCQ16() {
  let person1 = {
    name: { firstName: "Jayesh" },
    age: 24,
  };
  let person2 = { ...person1 };

  person2.name.firstName = "Virat";
  person2.age = 33;

  console.log(person1.name.firstName);
  console.log(person1.age);

  // 👍A) Jayesh, 33     💡B) Jayesh, 24
  // 💖C) Virat, 33      😀D) Virat, 24

  /*
  Answer is D) Virat, 24 because The spread operator makes deep copies of data if the data is not nested. 
  When we have nested data in an array or object the spread operator will create a deep copy of the top most data 
  and a shallow copy of the nested data. 
  person1 and person2 is pointing to different memory address but person1.name and person2.name is pointing to the same memory address

  We Can do Deep copy of nested objects by using:-
  1) const copyObj = JSON.parse(JSON.stringify(originalObj))
  2) const copyObj = structuredClone(originalObj);
*/
}
// MCQ16();

// 👉 MCQ-17
function MCQ17() {
  for (var i = 0; i < 5; i++) {
    setTimeout(
      (i) => {
        console.log(i);
      },
      1000,
      i
    );
  }

  // 👍A) 0 1 2 3 4      💡B) 5 5 5 5 5
  // 💖C) 4 4 4 4 4      😀D) 0 1 2 3 4 5

  /*
  Answer is A) 0 1 2 3 4 because as we are passing i ( 0 to 4 ) value as an argument to setTimeout callback function
  therefore this will console different values of i from 0 to 4.

  if there was no argument passed to setTimeout callback function then the output would be 5 5 5 5 5 because variables declared 
  with var keyword are function-scoped or globally-scoped but not blocked scoped. Inner function i would point to the updated value of i that is 5.
*/
}
// MCQ17();

// 👉 MCQ-18
function MCQ18() {
  console.log(1);

  async function fetchData() {
    console.log(2);
    let result = await Promise.resolve(3);
    console.log(result);
  }

  fetchData();
  console.log(4);

  // 👍A) 1 2 3 4      💡B) 1 4 2 3
  // 💖C) 1 2 4 3      😀D) 1 3 4 2

  /*
  Answer is C) 1 2 4 3 beacause promise is used to handle the asynchronous result of an operation and 
  callback functions attached to the promises are stored into microtask queue. 
  So, first synchronous code will be executed i.e 1,2,4 and once callstack is empty, event loop pushes the microtask queue's task into callstack
  callstack will start executing the task and It will console 3 at last.
  */
}
// MCQ18();

// 👉 MCQ-19
function MCQ19() {
  console.log("start");

  const promise = new Promise((resolve) => {
    console.log(1);
    resolve(2);
    console.log(3);
  });

  promise.then((result) => {
    console.log(result);
  });

  console.log("end");

  // 👍A) start end 1 3 2      💡B) start 1 3 end 2
  // 💖C) start end 1 2 3      😀D) start 1 end 2 3

  /*
  Answer is B) start 1 3 end 2 beacause The function we pass into the Promise constructor runs synchronously, 
  but anything that depends on its resolution ( resolve or reject ) will be called asynchronously. 
  Even if the promise resolves immediately, any handlers ( callback attached to promise then and catch ) will execute asynchronously. 

  const promise = new Promise((resolve) => {
  console.log(1);  // runs synchronously
  resolve(2); // called asynchronously by then callback
  console.log(3); // runs synchronously
});
*/
}
// MCQ19();

// 👉 MCQ-20
function MCQ20() {
  console.log("First");

  const promise = new Promise((resolve) => {
    console.log("Second");
  });

  promise.then((result) => {
    console.log(result);
  });

  console.log("Third");

  // 👍A) First Second undefined Third      💡B) First Third Second
  // 💖C) First Second Third undefined      😀D) First Second Third

  /*
  Answer is D) First Second Third because as there is no resolve in Promise constructor, So it will not go inside of .then block.
  */
}
// MCQ20();

// 👉 MCQ-21
function MCQ21() {
  const fetchData = function () {
    return new Promise((resolve, reject) => {
      reject();
    });
  };

  fetchData()
    .then(() => {
      console.log("Success 1");
    })
    .catch(() => {
      console.log("Error 1");
    })
    .then(() => {
      console.log("Success 2");
    });

  // 👍A) Error 1 TypeError    💡B) Error 1
  // 💖C) Error 1 Success 2    😀D) undefined

  /*
  Answer is C) Error 1 Success 2 because in promise chaining .then method below .catch method will be called if in .catch method we are not 
  returning rejected promise ( by default implicitly returns a promise that is handled by it's below .then method )
  */
}
// MCQ21();

// 👉 MCQ-22
function MCQ22() {
  function foo() {
    let a = (b = 0);
    a++;
    return a;
  }
  foo();
  console.log(typeof a);
  console.log(typeof b);

  // 👍A) undefined number        💡B) ReferenceError number
  // 💖C) undefined undefined     😀D) number number

  /* 
  Answer is A) undefined number because variable a is declared with let it is blocked scope and will be "not defined" outside function foo().
  The typeof operator returns "undefined" even for “undeclared” (or “not defined”) variables.
  Notice that there was no error thrown when we executed typeof a, even though a is an undeclared variable. 
  This is a special safety guard in the behavior of typeof. 
  and variable b is a just global scope variable hence it will be available outside function foo() also. 
  */
}
// MCQ22();

// 👉 MCQ-23
function MCQ23() {
  console.log("start");

  setTimeout(() => {
    console.log("first");
  }, 0);

  Promise.resolve("second").then((res) => console.log(res));

  console.log("end");

  // 👍A) start end first second       💡B) start first second end
  // 💖C) start end second first       😀D) start first end second

  /* 
  Answer is C) start end second first because callback function attached to Promises added into microtask queue 
  whereas callback function of setTimeout added into callback ( macroTask ) queue. 
  microTask queue has more priority than callback ( macroTask ) queue.
  */
}
// MCQ23();

// 👉 MCQ-24
function MCQ24() {
  const person1 = {
    name: "Jayesh",
    age: 24,
  };

  const person2 = person1;
  person2.name = "Virat";

  console.log(person1.name);
  console.log(person2.name);

  // 👍A) Jayesh Virat  💡B) Virat Virat
  // 💖C) Virat Jayesh  😀D) Jayesh Jayesh

  /* 
  Answer is B) Virat Virat because objects are passed as a reference, person1 and person2 will hold the same memory address
  and altering any property of person2 will modify property of person1 as well.
  */
}
// MCQ24();

