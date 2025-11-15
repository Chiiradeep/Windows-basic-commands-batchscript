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
~~~c
Remove the directory "my-folder"
~~~

<img width="771" height="132" alt="image" src="https://github.com/user-attachments/assets/4d925b88-798e-4e13-a2db-cad29d37dbdc" />


## COMMAND AND OUTPUT
~~~c
Create the file Rose.txt
~~~

<img width="636" height="135" alt="image" src="https://github.com/user-attachments/assets/24044db1-c1fc-4eaa-8b7f-23e336e59efc" />


## COMMAND AND OUTPUT
~~~c
Create the file hello.txt using echo and redirection
~~~

<img width="932" height="170" alt="image" src="https://github.com/user-attachments/assets/4fc2a212-5135-412a-a022-e0049a46d1bc" />


## COMMAND AND OUTPUT
~~~c
Copy the file hello.txt into the file hello1.txt
~~~

<img width="913" height="607" alt="image" src="https://github.com/user-attachments/assets/39983d07-45c0-4f75-94b5-a9b7f0f815a2" />


## COMMAND AND OUTPUT

~~~c
Remove the file hello1.txt
~~~

<img width="645" height="115" alt="image" src="https://github.com/user-attachments/assets/3d8b253c-85f7-4b69-aab7-4b0279ca576a" />

## COMMAND AND OUTPUT
~~~c
List out all the associated file extensions 
~~~

<img width="943" height="711" alt="image" src="https://github.com/user-attachments/assets/295d5420-5aa8-484b-86d6-d0078bd7274f" />


## COMMAND AND OUTPUT

~~~c
Compare the file hello.txt and rose.txt
~~~

<img width="615" height="220" alt="image" src="https://github.com/user-attachments/assets/f621be5d-dc14-49d4-841b-236b066615c6" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="891" height="212" alt="image" src="https://github.com/user-attachments/assets/29086a30-9e1d-4e32-a213-39e0365ce934" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="739" height="266" alt="image" src="https://github.com/user-attachments/assets/435406e6-ae97-4417-a14d-9b673184fe31" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="578" height="210" alt="image" src="https://github.com/user-attachments/assets/543d7746-293c-4971-96d0-1835ddc4e847" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="670" height="127" alt="image" src="https://github.com/user-attachments/assets/70e4455c-5f3a-443d-8056-d85d455e1bb5" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="846" height="415" alt="image" src="https://github.com/user-attachments/assets/f5266dec-b67f-493f-b020-9f2c9a10d452" />

# RESULT:
The commands/batch files are executed successfully.

