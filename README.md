# Natural-Language-processing-project
# Unit 6 - Natural Language Processing Project

## Introduction

Natural language processing (NLP) is used in many apps and devices to interact with users and make meaning of text to determine how to respond, find information, or to create new text. Your goal is to use natural language processing techniques to identify structure, patterns, and meaning in a text to have conversations with a user, execute commands, perform manipulations on the text, or generate new text.

## Requirements

Use your knowledge of object-oriented programming, ArrayLists, the String class, and algorithms to create a program that uses natural language processing techniques:

- **Create at least two ArrayLists** – Create at least two ArrayLists to store the data used in your program, such as data from text files or entered by the user.
- **Implement one or more algorithms** – Implement one or more algorithms that use loops and conditionals to find or manipulate elements in an ArrayList or String object.
- **Use methods in the String classs** - Use one or more methods in the String class in your program, such as to divide text into sentences or phrases.
- **Use at least one natural language processing technique** – Use a natural language processing technique to process, analyze, and/or generate text.
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions.

## UML Diagram

Put and image of your UML Diagram here. Upload the image of your UML Diagram to your repository, then use the Markdown syntax to insert your image here. Make sure your image file name is one word, otherwise it might not properly get display on this README.

![UML Diagram for my project](https://docs.google.com/drawings/d/1DM57xohiMMwM-mxVDHomH9di5vr_M_DrZ1W_fyW5bGM/edit)


## Video

Record a short video of your project to display here on your README. You can do this by:

- Screen record your project running on Code.org.
- Upload that recording to YouTube.
- Take a thumbnail for your image.
- Upload the thumbnail image to your repo.
- Use the following markdown code:

https://www.youtube.com/watch?v=pKS1xSmftbI


## Project Description

Write a description of the goal and/or problem that your application. Include descriptions of what text is being analyzed, either if its text files you are using to interpret text an how the user interacts with your project.

The programs purpose is to output hobbies based on user input. This will help the suser decide a randomized hobby to do from either the outside.txt or the inside.txt depending on if the user inputs outside, out, in, or inside. The input of wether inside or outside is being analyzed to output out of the .txt files lists that traverse and randomize a hobby out of the whole lst each time the program is run. There is also an option to outprint a randomized list of hobbies to do which again you can still choose outside or inside it will just print the first word of each sentance within the file in random order. For exmaple it wil ask inside or outside hobby and if i input inside it will give me a hobby from the inside.txt file list randomly as a sentance and then it will ask would you like a one word list of hobbies to do and will ask again inside or outside and if i choose ouside it will give me a lst of one word hobbies to do in a randomized order because the program is coded to traverse through each of the files lsts to output a random output based off the users input.

## NLP Techniques

Write a description of what natural lanugage technique (NLP) you implemented in your project. State which methods in your project are associated with this, and a brief explanation of how those methods word and how they are necessary in the NLP technique.

The TextProcessor.textToWords() method to break down text into individual words. The toDo.getOption() method randomly picks an activity from the selected list (outside.txt or inside.txt). It also simplifies suggestions by printing just the first word of each activity with toDo.printFirstWordOutside() and toDo.printFirstWordInside() afterwards when given the option to. The toDo.prompt() method analyzes the user's choice and outputs the cordinating topic from the .txt files. These techniques help the program generate outputs based on user input. 



