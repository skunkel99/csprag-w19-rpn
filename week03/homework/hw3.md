# EECS 201 HW 3
uniqname:  skunkel

## Question 1
``` 1
The command mkdir used to work, but stopped working when I set the Path to be empty. When I try to use mkdir, I get the following message: "-bash: mkdir: No such file or directory"
```

## Question 2
``` 2
Mkdir will create the directory in the directory of the given path only if the path already exists. Otherwise, mkdir will quit with an error message. Therefore, you cannot use mkdir if the path is empty, or does not exist. 
```

## Question 3
``` 3
The command pwd still works after reseting the path. pwd is a built in command, therefore still works when there is an empty path. Since it is built in and not based on the environment variable, pwd still works with an empty path; however, path is an evironment variable that shows which directories the shell can search to find a command that was typed.
```

## Question 4
``` 4
The '$?' variable represents the previous status of the exit commmand in the script. This could be helpful if you are trying to see what the exit command is of a program, particularly to see if a program goes over time.
```

## Question 5
``` 5
The variable '$1' is the first argument that is passed to the script from the command line. An example where this would be useful would be if you are trying to access a specific argument from the command line. Specifically, if the first argument tells you how to run the program, you could use $1 to access that.
```

## Question 6
``` 6
#!/bin/bash
gcc -o hello hello.c
./hello > output
gcc -o correct correct.c
./correct > correctoutput
diff -q output correctoutput > difference

if [ difference == "Files output and correctoutput differ" ]
then
  echo "Test failed. Expected output >>Hello World<<, got output >>{" output "}<<"
else
  echo "All tests passed."
fi

```

## Question 7
``` 7
To modify the path permanetely, I would put the following line in my bash profile: export PATH=$PATH:/my/custom/path. 
```

### Question 8
``` 8
It took a while to figure out the bash script, so I would say around 3 hours.
```