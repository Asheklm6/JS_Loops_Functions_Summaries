//Summary of JavaScript Array Methods https://www.w3schools.com/js/js_array_methods.asp

**JavaScript Array Methods**

1. **Array length**: This explains to you how many items are in an array.
   - *Example*: Imagine a shopping list. The length is like counting how many things you need to buy.

2. **Array toString()**:This Converts an array(number of items) into a string of values, separated by commas.
   - *Example*: Your favorite fruits listed: "Apple, Orange, Banana."

3. **Array pop() and push()**: `pop()` This removes the last item, `push()` adds an item to the end.
   - *Example*: Taking out the last fruit ("Mango") or adding a new one, like "Kiwi."

4. **Array shift() and unshift()**: `shift()` removes the first item, `unshift()` adds an item to the start.
   - *Example*: Taking out the first fruit ("Banana") or adding a new one, like "Lemon."

5. **Array join()**: Joins all array elements into a string, with a specified separator.
   - *Example*: Fruits joined with "*", like "Banana * Orange * Apple * Mango."

6. **Array delete()**: Removes an item, leaving a hole. Not recommended; use `pop()` or `shift()` instead.
   - *Example*: Deleting a fruit like "Banana" might leave an empty space.

7. **Array concat()**: Merges arrays to create a new one.
   - *Example*: Combining lists of names to make a bigger list.

8. **Array flat()**: Reduces the complexity of an array.
   - *Example*: Simplifying a list with smaller lists inside.

9. **Array splice() and slice()**: `splice()` adds/removes items at a position, `slice()` creates a new array from a section.
   - *Example*: Adding "Lemon" and "Kiwi" or taking out a part like "Orange" and "Lemon."

10. **Automatic toString()**: When you talk about your list, it naturally turns into words with commas.
    - *Example*: Saying your favorite colors turns into a list automatically.

//Summary of Javascript Functions https://www.w3schools.com/js/js_functions.asp
**Javascript Functions**

1. **Function**: This has to do with a set of instructions designed to do a specific job.
   - *Example*: Think of a recipe - it's a set of steps telling you how to bake a cake.

2. **Function Syntax**: This has to do with the steps involved to write a function in JavaScript.
   - *Example*: It's like defining a task with steps: `function makeCake(ingredients) { // instructions }`.

3. **Function Parameters and Arguments**: Information passed into a function.
   - *Example*: In a pizza-making function, `ingredients` are the parameters. When you make a specific pizza, like "Pepperoni," those details are the arguments.

4. **Function Invocation**: When and how the function gets executed or used.
   - *Example*: It's like pressing the "Start" button on a blender to make a smoothie.

5. **Function Return**: What a function gives back as an answer.
   - *Example*: If you ask a calculator function `add(2, 3)`, it gives back `5`.

6. **Why Functions?**: Why use functions - they're like reusable tools in coding.
   - *Example*: Imagine having a magic wand that you can use for different spells whenever you need them.

7. **Using Functions**: How you apply functions in your code like you do with math.
   - *Example*: If you have a formula `multiply(4, 5)`, it gives `20`.

8. **The () Operator**: How you call a function to use it.
   - *Example*: Like dialing a friend's number to make a call, `toCelsius(77)`.

9. **Functions with Incorrect Parameters**: Using a function wrongly can give the wrong answer.
   - *Example*: Asking a function for the Celsius value without providing a Fahrenheit value might give you an incorrect answer.

10. **Functions Used as Variable Values**: Using functions directly in your code instead of storing them in a variable first.
    - *Example*: Instead of storing your age in a variable `age = calculateAge(2000)`, you can directly say `"I'm " + calculateAge(2000) + " years old"`.

11. **Local Variables**: Variables declared inside a function, only accessible within that function.
    - *Example*: Like a secret code only known and usable within a club.


//Summary on Javascript Functions https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions
**Key points about JavaScript functions**

1. **What's a Function?**: It's a mini-program that does a specific task when you tell it to.

2. **Function Job**: Functions take instructions, work with them, and might give you something back.

3. **How to Use**: You call a function by using its name and, if needed, giving it some info (arguments).

4. **Return Gifts**: Functions can give you results. If they don't, it's like they give you 'nothing' (technically, `undefined`).

5. **Flavors of Functions**:
   - Basic ones: Do a task, give back something.
   - Fancy ones: Can pause (for some) and work in the background (async).

6. **Ways to Write Functions**:
   - Say it directly: `function name() { // job }`
   - Hide it in a box: `const name = function() { // job }`
   - Use a cool arrow: `const name = () => { // job }`

7. **Special Jobs**:
   - Some functions are like secret agents, they live only in certain areas (blocks).

8. **Get and Set Functions**: 
   - Imagine if your data had bodyguards. These functions act like bodyguards for data.

9. **Flexible Parameters**: 
   - Functions can be chill and work with various kinds of information you give them.

10. **Decide Later**: 
    - You can even decide if you want a function later. It's like saying, "If I need this, here it is."

11. **Examples**:
    - A helper function that adds zeros to numbers.
    - Checking if a certain function exists before using it.

//Summary on Function Basics https://javascript.info/function-basics

**Function Basics**

1. **Creating a Function**:
   - You give it a name, like "makeJollofRice," and jot down the steps needed, like: wash rice, chop vegetables, fry ingredients, cook rice, mix everything, etc.

2. **Using a Function**:
   - When you want to actually make Jollof rice, you follow those steps by using the "makeJollofRice" function.

Now, imagine you're flexible about the ingredients. Sometimes you might want to add more spices or change the type of meat or veggies used.

- **Parameters** in a function are like those ingredients. For the "makeJollofRice" function, the parameters could be things like "type of meat," "amount of spice," or "type of rice." These parameters can be different each time you make Jollof rice.

And after following the steps (executing the function), you have your finished Jollof rice!

- **Return Values** could be something like how tasty the rice is or maybe the quantity you've made. It's what you get back after using those instructions.





