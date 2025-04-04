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
- Create a new file named `hello.js` in the Week1 folder
- This will be the file where you write your first JavaScript code

## Step 2: Write your first program
- In `hello.js`, write code that:
  - Creates a variable with your name
  - Uses `console.log()` to display a greeting message including your name
  - Uses `console.log()` to display a second message about what you hope to learn in this class

## Step 3: Commit your changes
- Add your new file to Git using the command line
- Create a commit with a descriptive message
- Push your changes to your GitHub repository

## Step 4: Verify your submission
- Go to your GitHub repository in a web browser
- Navigate to the Week1 folder
- Confirm that your `hello.js` file appears with the code you wrote

## Expected Output
When someone runs your program, they should see:
- A personalized greeting with your name
- A message about what you want to learn in this class

> 💡 **Challenge (Optional)**
> 
> Can you add a third message that calculates and shows how old you'll be in 5 years?