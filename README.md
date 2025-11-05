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
<img width="554" height="139" alt="Screenshot 2025-11-05 102700" src="https://github.com/user-attachments/assets/994708b4-ccd1-47d8-aed9-340a9c3086da" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="697" height="170" alt="Screenshot 2025-11-05 102710" src="https://github.com/user-attachments/assets/61300fe7-0681-4b95-bb8a-cf4e77ec2942" />


## COMMAND AND OUTPUT

Create the file Rose.txt
<img width="523" height="148" alt="image" src="https://github.com/user-attachments/assets/f793ff41-8423-4a11-bbb6-36fd906dad11" />


## COMMAND AND OUTPUT
Create the file hello.txt using echo and redirection


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="598" height="185" alt="Screenshot 2025-11-05 111509" src="https://github.com/user-attachments/assets/e44643a1-6766-40ad-b789-92cfa9c26c87" />


## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="472" height="189" alt="Screenshot 2025-11-05 111627" src="https://github.com/user-attachments/assets/c7c2a8d1-8a9f-4a6d-ad93-ebb46fc9c748" />


## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="423" height="217" alt="Screenshot 2025-11-05 111637" src="https://github.com/user-attachments/assets/b4462cda-145a-419e-9a59-6174a62ecb61" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt
<img width="579" height="210" alt="Screenshot 2025-11-05 111748" src="https://github.com/user-attachments/assets/05f1e645-7385-4c1d-94b1-5ff2ff694631" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT

<img width="444" height="143" alt="Screenshot 2025-11-05 113143" src="https://github.com/user-attachments/assets/b4fd4203-b88c-4df5-bcae-a56e3d28737c" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="578" height="264" alt="Screenshot 2025-11-05 113153" src="https://github.com/user-attachments/assets/b0b68e13-b0a5-4802-9890-aa0c33f37dba" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="501" height="231" alt="Screenshot 2025-11-05 113201" src="https://github.com/user-attachments/assets/fedab230-9590-4861-bf98-f6382809342c" />

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="644" height="271" alt="Screenshot 2025-11-05 113211" src="https://github.com/user-attachments/assets/1c3a92ce-ca6a-449d-a4f0-5cda9cdce865" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="515" height="509" alt="Screenshot 2025-11-05 113219" src="https://github.com/user-attachments/assets/6f470496-bd67-401f-9450-f56ec06ef9ab" />



# RESULT:
The commands/batch files are executed successfully.

