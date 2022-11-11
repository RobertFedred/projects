In this step our first task is to give id's to all the elements.

The id can be given like this

<div id = "stone" >

For exapmple here 'stone' is the id of the element <div>

Note: The id can be anything.

After giving the Id start making functions for the user options

For this you should know what are funtions.

if you know, Follow along

Give a funtion 'result()' on click inside the element

For exapmle

<div id="stone" onclick = "result()">

Now, In the script.js file make a function result(n).

Here in the parameter 'n' is the input which you will give onclick event

For example 
Stone -->   <div id="Stone" onclick = "result(0)">
Paper -->   <div id="Paper" onclick = "result(1)">
Scissor --> <div id="Scissor" onclick = "result(2)">

The user choice is the n and the computer choice is the random number between 0-2 so,that we can compare both of them.

The basic logic for this will be

User       Computer      Result
Stone/0    Paper/1       User won

Similarly, Make logic for rest of the combinations

You can use if/else conditionals for the logic.
