## JS Debugging
In this chapter I learned about the console and DEV tools, these are tools built in the browser that help you hunt for errors. Commin problems and common source of errors and how to solve them. Handling errors , how code can deal with potential errors gracefully.

##How to deal with errors
-Debug the script to fix errors, 
If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it.

-Handle errors gracefully
You can handle errors gracefully using try, catch,
throw, and f i na1ly statements.

-Where is the problem, First, should try to can narrow down the area where the problem seems to be. In a long script, this is especially important.

-What Exactly is the problem,Once you think that you might know the rough area in which your problem is located, you can then try to find the actual line of code that is causing the error.

Browers come with developer tools and Javascript consoles. 
The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be.When you are debugging errors, it can help if you look at the error in more than one browser as they can show you different error messages.Ifyouopentheerrors.html filefromthesample code in your browser, and then open the console, you will see an error is displayed.

avaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the errors, If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.