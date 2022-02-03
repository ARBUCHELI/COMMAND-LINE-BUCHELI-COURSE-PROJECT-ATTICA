# COMMAND-LINE-BUCHELI-COURSE-PROJECT-ATTICA

## Attica
Attica, a clothing store, has asked you to help them configure their environment.

## Tasks
18/18 Complete
Mark the tasks as complete by checking them off
* 1.
Print the working directory.


Hint
To display the current working directory, use:

```pwd```
* 2.
Create and open a file in nano called hello.txt.


Hint
Create and open a file with nano like so:

```nano filename.txt```
* 3.
Save the string, “Hello, I am nano” in hello.txt.

Save the file, exit nano, and clear the terminal.


Hint
Once nano is open, type in the string. To save and exit, type these keys in the following order:

```Ctrl + O```
Enter
```Ctrl + X```
To clear the terminal, use the clear command.

* 4.
Use nano to open the bash profile.


Hint
Open a file with nano like so:

```nano filename.txt```
The path to the bash profile is ~/.bash_profile

* 5.
In the bash profile, add a greeting with the word “Hello” using the echo command. Save the file, exit nano, and clear the terminal.


Hint
Once the bash profile is open, type in echo and the string “Hello” on the same line.

To save and exit, type these keys in the following order:

```Ctrl + O``` 
Enter
```Ctrl + X```
To clear the terminal, use the clear command.

* 6.
Use the source command to make the greeting available in the current session.

You should see the greeting you created.


Hint
To execute the content that we’ve just updated the bash profile with, use:

```source ~/.bash_profile```
* 7.
Open the bash profile, and create two aliases. The first alias should be p for the pwd command and ll for the ls -la command.

Save the file, exit nano, and clear the terminal.


Hint
To make an alias in bash profile, use the following format on a new line:

```alias aliascommand="originalcommand"```
* 8.
Use the source command to make the aliases available in the current session.


Hint
To execute the content that we’ve just updated the bash profile with, use:

```source ~/.bash_profile```
* 9.
Test out the aliases you created for the pwd and ls -la command.


Hint
The alias we created for pwd is:

```p```
The alias we created for ls -la is:```

```ll```
Type each of them after the command prompt.```

* 10.
Open the bash profile and create and export the USER environment variable, setting it equal to your name.

Save the file, exit nano, and clear the terminal.


Hint
To export an environment variable, type the following format in the bash profile:

```export VARIABLE="Value"```
In this case, the environment variable is USER and the value is your name.

* 11.
Use the source command to make the aliases available in the current session.


Hint
To execute the content that we’ve just updated the bash profile with, use:

```source ~/.bash_profile```
* 12.
Echo the USER variable.


Hint
To echo an environment variable, use echo and the variable name (with a $ in front of it).

```echo $VARIABLE```
* 13.
Open the bash profile and create and export the PS1 environment variable, setting it equal to ">> ".

Save the file, exit nano, and clear the terminal.


Hint
To export an environment variable, type the following format in the bash profile:

```export VARIABLE="Value"```
In this case, the environment variable is PS1 and the value should be ">> ".

* 14.
Use the source command to make the prompt available in the current session.


Hint
To execute the content that we’ve just updated the bash profile with, use:

```source ~/.bash_profile```
* 15.
Test out the prompt by typing the two aliases you created earlier.


Hint
The alias we created for pwd is:

p
The alias we created for ls -la is:

ll
Type each of them after the new command prompt.

* 16.
Echo the HOME variable.


Hint
To echo an environment variable, use echo and the variable name (with a $ in front of it).

```echo $VARIABLE```
* 17.
Echo the PATH variable.


Hint
To echo an environment variable, use echo and the variable name (with a $ in front of it).

```echo $VARIABLE```
* 18.
Return a list of environment variables.


Hint
```env```
returns and displays the list of environment variables.
