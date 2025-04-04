# Lesson-1
Welcome to your first lesson!

## 1 Generating an SSH key and adding it to your profile

- Run `ssh-keygen -t ed25519` in your terminal and hit enter until it stops prompting. Note the path where it is creating the key.
- Navigate to the path where the key has been created. This will typically be in `~/.ssh`.
- Print the public key to the terminal so it can be copied by running cat `~/.ssh/id_ed25519.pub`

> 💡 **Note**
> 
> Go to your tutor once you have done this with the key in your terminal.


# Task 1: Hello JavaScript World!

In this task, you'll create your first JavaScript program and push it to GitHub. Follow these steps:

## Step 1: Create a new file
- Create a new file named `hello.js` in the Lesson-1 folder
- This will be the file where you write your first JavaScript code

## Step 2: Write your first program
- In `hello.js`, write code that:
    - Print your name to the terminal!

## Step 3: Commit your changes
- Add your new file to Git using the command line `git add .`
- Create a commit with a descriptive message `git commit -m "THIS IS A VERY DESCRIPTIVE MESSAGE"`
- Push your changes to your GitHub repository `git push`

## Step 4: Verify your submission
- Go to your GitHub repository in a web browser
- Navigate to the Lesson-1 folder
- Confirm that your `hello.js` file appears with the code you wrote

# Task 2: Variables

What are variables?

## 2 Understanding `let` and `const` in JavaScript

### `let` Variables

The `let` keyword creates variables that can be reassigned later in your code:

```javascript
let score = 10;
console.log(score); // Outputs: 10

score = 20;         // Changing the value
console.log(score); // Outputs: 20
```

`let` is block-scoped, which means the variable only exists within the nearest set of curly braces `{}` (a block). This makes `let` great for loop counters or any value that needs to change.

### `const` Variables

The `const` keyword creates variables whose values cannot be reassigned:

```javascript
const playerName = "Alex";
console.log(playerName); // Outputs: Alex

// playerName = "Sam"; // This would cause an error!
```

Important notes about `const`:
- Once declared, you cannot assign a new value
- Must be assigned a value when declared
- Also block-scoped like `let`
- Objects and arrays declared with `const` can still have their properties modified:


### When to use which?

- Use `const` by default (prevents accidental reassignment)
- Use `let` when you know the variable will need to change

For beginners, a good rule of thumb: if you need to change a variable later (like a score, counter, or accumulator), use `let`. For everything else, use `const`.

There is a file called `variables.js`, open this file and finish the tasks!

## Step 1: Create different types of variables
- Create a variable with your name (text)
- Create a variable with your age (number)
- Create a variable with your favorite hobby (text)

## Step 2: Experiment with variable operations
- Try adding your name and your hobby together with the + sign
- Try adding your age and the number 10
- Try multiplying your age by 7
- Try putting your name in quotes and then adding it to your age

## Step 3: Output your results
- Use `console.log()` to display each of your experiments
- Add a short comment before each output to describe what you're testing

## Step 4: Break things on purpose!
- Try at least one thing you think might cause an error
- For example, what happens if you try to multiply your name by 5?
- Use `console.log()` to display the result (if any)

## Step 5: Save and push your code
- Commit your file to your repository
- Push the changes to GitHub

## Expected Output
Your program should display several results showing what happens when you:
- Combine text variables
- Perform math on number variables
- Mix different types of variables together


