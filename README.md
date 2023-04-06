# Name: Darshit Bhakhar
# ID: 202001453
# Lab-05

Link of Git Repository taken: 
https://github.com/python/typeshed.git

# Tools used for static Analysis: Pylint

Link of github repository taken:
https://github.com/python/typeshed.git

![image](https://user-images.githubusercontent.com/124347126/227472823-1e209f19-972c-4f13-bb71-8f7bbb2eeec7.png)

In runtests.py file present in: https://github.com/python/typeshed/tree/main/scripts

![image](https://user-images.githubusercontent.com/124347126/227474722-7c2452cb-0f22-4ab8-866c-7a933623ffbb.png)

In stubsabot.py file present in: https://github.com/python/typeshed/tree/main/scripts

![image](https://user-images.githubusercontent.com/124347126/227475196-ff317f12-59f8-4e28-8842-50a3f794dcd1.png)

![image](https://user-images.githubusercontent.com/124347126/227475518-22411fe8-439f-473d-a3ab-8c7175c56bb7.png)

![image](https://user-images.githubusercontent.com/124347126/227482341-f0a212e3-20fc-4634-8530-f1d7ecf94658.png)

# Error Analysis:
  C0115/C0116: Missing function or method docstring (missing-function-docstring )/ Missing class docstring (missing-class-docstring) This type of error is shown when docstring is not written for a given function/class/object. Docstring is basically a description that describes what function/object is doing, its parameters and its return value. It is a good practice to write docstring for all functions/objects/classes.

  C0103: Variable name “zf” does not conform to snake_casenaming style. Snake case (ex: snake_case) is commonly used in scripting languages like Python. It is showing error because the variable name is not following the snake case as variable name length is less than 3 symbols.

  C0301: Line too long (112/100) (line-too-long) This error is shown when the number of characters is more than suggested for ideal reading. More number of characters/symbols present on a single line decreases the logical understanding of the code and makes code more difficult to read.

  C0103: Variable name “nothing” does not conform to UPPER_CASE naming style (invalid naming). As your code is not contained in a class or function it is expecting those variables to be constants and as such they should be uppercase.

  C0325: Unnecessary parens after the ”if” keyword (superfluous parens). It shows error when a single item in parentheses follows an if, for, or other keyword.

  R0914: Too many local variables (20/15) (too-many-locals) This error is shown as an indicator that the function or method is too complex, or trying to do too much.

  R0912: Too many branches. This error is shown as the function or method has too many branches, making it hard to follow.

  W0613: Unused argument ”color” (unused-argument) This error is shown when the function is taking an argument but not using it inside the function.
