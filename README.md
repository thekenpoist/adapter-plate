# adapter-plate
## G-code with Macros example for CNC machinery

### G-code explained
```
G-code, also known as RS-274, is the standard programming language 
for CNC (Computer Numerical Control) machines. It is used to instruct 
CNC machines on how to move, what path to follow, and how to perform 
specific actions to create precise parts from various materials. 
```

### Macros explained
```
Macros programming for Haas CNC machines involves creating custom 
G-code programs using variables, conditional statements, and loops 
to automate complex machining operations and enhance flexibility.

By using macros, programmers can enhance the efficiency and functionality 
of their CNC programs, allowing for more sophisticated and automated 
machining processes on CNC machineery.
```

### The adapter-plate example
```
In this program, macros are used to read operator input of machine local 
parameters to control the process flow by implementing multiple IF/GOTO 
statements. Macros also access machine global parameters to manipulate 
tool geometry at the parameter level through numerous IF/THEN statements. 
Additionally, a WHILE/DO loop is incorporated into the program for continuous 
running of the G-code to produce five parts from one slug before ceasing 
operation. These tasks simplify the machine operator's job by automating 
processes that are normally done manually, thereby eliminating the risk of 
operator error that could cause a machine collision incident, commonly 
referred to as a "crash."
``` 
