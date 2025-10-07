**Evil Hangman Design**  

**Team Members: Aryav Das and Garrett Hur**

Review the project description/requirements carefully then consider what classes are needed to solve the problem. For each class, you need to determine the instance fields and methods it will include. Once this is finalized, you should document all the classes, instance fields and methods. Example documentation is below. Next, you need to create pseudocode for your main method of your Driver class. An example of this is also given. You may find it helpful to do a "walkthrough" of your program logic with sample data to help ensure all necessary functionality is accounted for. Of course, all of this is going to take time and energy to produce. Why do you think this step is so critical in software development?

**Dictionary**

***Instance Fields:***  
private ArrayList\<String\> wordList;

***Methods:***  
public Dictionary(String fileName) \- Constructs a Dictionary based off the words located in the file given as an argument. 

public boolean hasWordsOfLength(int len) \- Returns true if the Dictionary has words of the given length; false otherwise. 

public ArrayList\<String\> getWordsOfLength(int len) \- Returns an ArrayList of words of the given length.

**WordFamily**

***Instance Fields:***  
…

***Methods:***  
…

*ADD OTHER CLASSES YOU WANT*

**Driver Pseudocode**

Create a Dictionary object, passing the file you want to read from  
boolean playAgain \= false;

do {  
     do {  
        ask the user for the word length  
        if the given word length is invalid  
            display error message  
     } while(the word length is invalid);  
     . . .

} while(playAgain);

