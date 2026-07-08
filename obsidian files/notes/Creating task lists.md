
There are many apps out there for managing tasks, and they surely work fine, but I think that it's pretty hard to argue with the idea of having all of your tasks grouped right with the rest of your notes and thoughts. For these reasons, I would like to propose some examples of ways of making task lists in Obsidian. 


## Creating a task class

The first and most obvious way of creating task list is by creating a class to represent each task. This is very handy, and I think that this is one of the cleaner methods. But I'll try to let the structure speak for itself. 




### The basic implementation

In the most basic form of a task list, tasks only have two states:
1. Done
2. Not done

This is very easy to model using a simple [[templates|template]] + [[bases|base]] setup.

##### Example 



![[Creating task lists-1.png]]

![[Creating task lists.png]]





In my todo (or task) template, I simply add a `done` field with the property type of *checkbox*. Thereafter, in my base, I group my notes based on the `done` property, so that I can see what I have done and what I still need to do. If would like to group your notes based on a different property (like `type of todo`) then I would suggest filtering out notes where done is true. Then simply add another view to the base where you can see the tasks which you have already completed. 

As you can also see, I have many more properties like `urgence`, `what to do`, and `type of todo` to further contextualize my tasks and really stay on top of things. You can be as creative as you want when it comes to creating the [[metadata]] for you classes! 

---


![[Creating task lists-2.png]]


Another possibility is the creation of sub views in the base to allow for different types of tasks. Anything is possible! 




### A more complexe implementation




The above implementation of a task list is perfect for simple things, but what if we want to have a more clear view of what really matters in the moment. In this case, we might consider an implementation of tasks which is described perfectly in this video: [[Obsidian Bases--Obsidian's Biggest Upgrade (Complete Guide)]] at the `39:23` timestamp. Here, Nick Milo explains his personal philosophy for tasks, which involves the use of three stages:
1. active
2. simmering
3. sleeping


The implementation of these three things works in the exact same way as what I described above with the simpler task list (although Nick Milo implements it using folders, which I do not recommend doing).




