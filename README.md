# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT

<img width="942" height="326" alt="image" src="https://github.com/user-attachments/assets/8a714749-ade6-40e9-b4bb-8bb48daf868d" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="851" height="251" alt="image" src="https://github.com/user-attachments/assets/4cc99896-8aa6-46e4-879c-fe3db0f34262" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="867" height="410" alt="image" src="https://github.com/user-attachments/assets/e079cb95-739c-48d7-9117-42941f5fa018" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="925" height="187" alt="image" src="https://github.com/user-attachments/assets/52f29f59-eca9-4b77-a789-27b6fa2db6a0" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="933" height="130" alt="image" src="https://github.com/user-attachments/assets/fddc7876-4e19-4a89-883c-44219a97da62" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="861" height="92" alt="image" src="https://github.com/user-attachments/assets/fb363f07-f9e0-4ca8-8390-69a2b6f786d3" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="847" height="172" alt="image" src="https://github.com/user-attachments/assets/686af5db-2a4b-4d1d-9723-94eaaeeb6f3c" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="885" height="952" alt="image" src="https://github.com/user-attachments/assets/ee7f23dc-a1ae-4327-af2e-85b52c6f74b7" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="900" height="195" alt="image" src="https://github.com/user-attachments/assets/c2e4f848-c722-4bf6-8792-bcbfb43fdaab" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT

<img width="673" height="122" alt="image" src="https://github.com/user-attachments/assets/9016d091-5098-467f-94cd-e709dcbe9306" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="722" height="203" alt="image" src="https://github.com/user-attachments/assets/40ce2992-5fe4-46e5-87c3-3cca92684edb" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="700" height="166" alt="image" src="https://github.com/user-attachments/assets/f256fa55-9071-4bb8-a84f-fd75f602c09c" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="1042" height="210" alt="image" src="https://github.com/user-attachments/assets/aadb900e-4492-4274-bff2-9358109ec30c" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="837" height="362" alt="image" src="https://github.com/user-attachments/assets/1e465159-8090-483a-b6ab-d65eec6c6602" />




# RESULT:
The commands/batch files are executed successfully.

