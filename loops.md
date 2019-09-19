# Learning Loops

Loops check a condition.  If the condition returns true, a code block will run.  The condition will be continued to be checked, and as long as it's true, the code will run again.  If the condition returns false, the code will stop.

The 2 types of loops we learned about today are for and while.

An example of a **for** loop is:

    for (var i = 0; i< 10; i++){ 
        document.write (i);
    }

this means that since your vaiable i has the value of zero, it is less than 10, so 0 will be written on the page.  Then the i variable will be incremented by 1.  This will continure until the value of i has been incremented until it is no longer less than zero.

For loops are typically used when the number of iterations is known before entering the loop.

And example of a **while** loop is:

    var answer = ''
    while (answer === ''){
        prompt ('Do you like dogs?';)
    }
    
While loops are more dynamic, than for loops,s and you usually use them for lists or until a certain expression meets a criteria.
