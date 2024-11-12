1. What is the shell? The shell is basically a program that takes your commands from the keyboard and sends them to the operating system to perform.Try some other Linux commands and see what they output:
$ date $ whoami = $ date= Wed Oct 23 17:26:17 2024  $ whoami= nadja
What should be outputted to the display when you type echo Hello World? $ echo Hello World = Hello World

2.pwd (Print Working Directory)
Exercises = No exercises for this lesson Quiz  
Quiz How do I find what directory you are currently in? =  pwd

3.cd (Change Directory)
Run the cd command without any flags, where does it take you?= No Answer
Quiz: If you are in /home/pete/Pictures and wanted to go to /home/pete, what’s a good shortcut to use? = cd ..

4.ls (List Directories)
Run ls with different flags and see the output you receive:
ls -R: recursively list directory contents =  it  shows you detailed information about the files and directories you are looking at
ls -r: reverse order while sorting = shows you information about a few files by reversimg the order and sorting them  
ls -t: sort by modification time, newest first = shows the newest saved files first 
Quiz What command would you use to see hidden files? = ls -a

5.touch
Exercises
Create a new file: touch mysuperduperfile
Note the timestamp: Oct 30 12:18  mysuperduperfile
Touch the file and check the timestamp once again:
Quiz How do you create a file called myfile?: touch myfile

6. file
Quiz
What command can you use to find the file type of a file? = file
Run the file command on a few different directories and files and note the output.= Command: $ file c\Users\nadja\Downloads\lebenslauf_Nadja_Debrezion_ (3).docx
bash: syntax error near unexpected token `('

7. cat
Quiz
What's a good way to see the contents of a file?=cat
Run cat on different files and directories. Then try to cat multiple files.= $ cd /c/Git\ hub, $ echo "hello" > textfile.txt, $ cat textfile.txt hello

8. less
Quiz
How do you quit out of a less command?= q
Run less on a file, then page up and around the file. Try searching for a specific word. Quickly navigate to the beginning or the end of the file.= $ less /c/Git\ hub/textfile.txt

9. history
Quiz
What is the command to clear the terminal?= clear
Exercises
Navigate through your previous command history with the Up and Down keys. Play around with ctrl-R reverse search.= (reverse-i-search)`':= no outcome

10.cp (Copy)
Quiz
What flag do you need to specify to copy over a directory?= -r
Exercises
Copy over a couple of files, be careful not to overwrite anything important.= $ cp /c/Git\ hub/textfile.txt /c/Users/nadja/Downloads

11.mv (Move)
Quiz
How do you rename a file called cat to dog?= mv cat dog
Exercises
Rename a file, then move that file to a different directory.= $ mv textfile.txt text, mv /c/Git\ hub/text /c/Users/nadja/OneDrive/Bilder

12.mkdir (Make Directory)
Quiz
What command is use to make a directory?=  mkdir
Exercises
Make a couple of directories and move some files into that directory.=$ mkdir Farben,$ mkdir books paintings,$ mv /c/Users/nadja/OneDrive/Dokumente/textfile.txt /c/Git\ hub/Farben

13. rm (RemoveQuiz
How do you remove a file called myfile?= rm myfile
Exercises
Create a file called -file (don't forget the dash!). Remove that file.= $ touch -- -file, $ rm -- -file

14.Find
Quiz
What option should I specify for find if I want to search by name? =-name
Exercises
Find a file from the root directory that has the word net in it.=

15.help
Quiz
How do you get quick command line help for built-in bash commands?=help
$ help echo
echo: echo [-neE] [arg ...]
    Write arguments to the standard output.
Display the ARGs, separated by a single space character and followed by a
newline, on the standard output.

$ help logout
logout: logout [n]
    Exit a login shell.
    Exits a login shell with exit status N.  Returns an error if not executed
    in a login shell.

$ help pwd
pwd: pwd [-LPW]
    Print the name of the current working directory.

16. man
Quiz
How do you see the manuals for a command?=
$ ls
'01-introduction (1).pdf'   Farben/   books/   file   paintings/



















































