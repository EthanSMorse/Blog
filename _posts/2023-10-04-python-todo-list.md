<h1>Python ToDo List</h1>

<br>

My most recent project was that of a python ToDo list.

The process was pretty straight forward, as we have done something like this once before in a much larger depth.

I first started making an empty list, the one that would be filled by the user. 

```
todo = []
```

I did make a small mistake here initially, by putting quotation marks inside of the brackets. This added an item to the list, which is not what I wanted to happen. I quickly remedied this simply by removing the quotation marks.

I next set up a while loop, which would make the  code run indefinietly once the vale was set to 1, or True.

```
while (1):
```

And now comes trhe most important part of the code: the conditionals. These would allow the user to control what they wanted to do with the list, whether it be add, remove, or check. Then, depending on whatever the user chose, it would go down that line of code and play it out, until simply looping into another iteration. For example, if the user input "add" or "Add", it would go down the first path, allowing the user it input a todo, which wout then be added to the list using the .append command.

```
if (app == "add" or app == "Add"):
        print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~")
        added = input("What would you like to add? ")
        todo.append (added)
        print(todo)
        print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~")
    elif (app == "remove" or app == "Remove"):
        print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~")
        remove = int(input("Which numbered item do you want to remove? "))
        del todo [remove - 1]
        print(todo)
        print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~")
    elif (app == "check" or app == "Check"):
        print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~")
        print(todo)
        print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~")
    else:
        print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~")
        print("The command you input is invalid. Please try again.")
        print("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~")
```

I didnt really end up having any problems with this code, except for the minor error at the beginning. All in all, wit was pretty simple.