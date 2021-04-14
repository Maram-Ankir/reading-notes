# Error Handling and Debugging

* Order of execution in JavaScript is dependent on the following components working together to pass and order information.

1-The Callstack.

2-The Event Loop.

3-The Task Queue.

4-WebAPIs/External Resources.

* The first two execution contexts correspond with the notion of scope:

-GLOBAL SCOPE

-FUNCTION-LEVEL SCOPE

* Debugging is about deduction: eliminating potential causes of an error.

* The JavaScript console will tell you when there is a problem with a script, 
where to look for the problem, and what kind of issue it seems to be.  

* You can also just type code into the console and it will show you a result. 

* Browsers that have a console have a console object, which has several methods that your script can use to display data in the console.


* If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code. 

* Debugging is the process of finding errors. It involves a process of deduction. 

* The console helps narrow down the area in which the error is located, so you can try to find the exact error. 

* JavaScript has 7 different types of errors. Each creates its own error object,
 which can tell you its line number and gives a description of the error. 

* If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. 


