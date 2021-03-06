# Welcome to Jeopardy!

## How to Play
If you've never heard of Jeopardy, now's the chance! Here's how to play:

You will be presented with the start up screen. Simply click 'start' and you're on your way to riches! There will be question values presented to you under specified categories, but you won't know what each question is. Select one of them and you'll be playing to win that much money! Get the question wrong and you'll lose that amount! Once you've completed all the questions, simply reset the game to play again. 

You can also add your own questions! 
[Read below to find out how](#adding-categories-and-questions)

## Screenshots
<div>
  <img src="./img/start.png" alt="Start" width=49.7%/>
  <img src="./img/question-board.png" alt="Question Board" width=49.7%/>
  <img src="./img/question.png" alt="Question" width=49.7%/>
  <img src="./img/correct.png" alt="Correct" width=49.7%/>
</div>

## Requirements
- You must have a [Java Runtime Environment (JRE)](https://www.oracle.com/java/technologies/javase-jre8-downloads.html) installed on your system
- If you encounter a JNI error, try installing the [Java11 JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) for your system

## Download
##### Note: It is very important that you have at least one category and that the categories folder is in the same directory as the .jar file

### Linux
1. [Download](https://github.com/SOFTENG206-2020/assignment-2-beverleysun/raw/master/Jeopardy-Linux.jar) the Jeopardy-Linux.jar file
2. [Download](https://github.com/SOFTENG206-2020/assignment-2-beverleysun/raw/master/categories.zip) the categories.zip file
   - Alternatively, you can create your own categories and questions. [See below for how to do this](#adding-categories-and-questions)
   - Unpack the .zip and move the 'categories' folder into the same directory as Jeopardy-Linux.jar
4. Open the terminal and execute the following commands
   ```
   > cd "path/to/jar"
   > chmod +x Jeopardy-Linux.jar
   > java -jar Jeopardy-Linux.jar
   ```
   
### Windows
1. [Download](https://github.com/SOFTENG206-2020/assignment-2-beverleysun/raw/master/Jeopardy-Windows.jar) the Jeopardy-Windows.jar file
2. [Download](https://github.com/SOFTENG206-2020/assignment-2-beverleysun/raw/master/categories.zip) the categories.zip file
   - Alternatively, you can create your own categories and questions. [See below for how to do this](#adding-categories-and-questions)
   - Unpack the .zip and move the 'categories' folder into the same directory as Jeopardy-Linux.jar
3. You can now simply double-click the .jar and the game should run
4. Alternatively, you can execute the following commands in the command line
   ```
   > cd "path/to/jar"
   > java -jar Jeopardy-Windows.jar
   ```

### Mac
1. [Download](https://github.com/SOFTENG206-2020/assignment-2-beverleysun/raw/master/Jeopardy-Mac.jar) the Jeopardy-Mac.jar file
2. [Download](https://github.com/SOFTENG206-2020/assignment-2-beverleysun/raw/master/categories.zip) the categories.zip file
   - Alternatively, you can create your own categories and questions. [See below for how to do this](#adding-categories-and-questions)
   - Unpack the .zip and move the 'categories' folder into the same directory as Jeopardy-Linux.jar
3. You can now simply double-click the .jar and the game should run
4. Alternatively, you can execute the following commands in the terminal
   ```
   > cd "path/to/jar"
   > java -jar Jeopardy-Mac.jar
   ```

## Adding Categories And Questions
You may add your own categories and questions as long you follow the correct format.
- The category file must be a plain text file
- It must be located within the 'categories' folder
- The 'categories' folder must be in the same directory that the .jar file is in
- You may not change the name of the 'categories' folder however, you can name the category file whatever you like
- Each question within a category must be separated by a new line
- Within each question, the format is as follows:
  - value,question,answer
    - So, the line must start with the question value (it must be an integer), followed by a comma, then the actual question, followed by a comma, then the answer.
  - One example might be: *100,The largest country by area in the world,Russia*