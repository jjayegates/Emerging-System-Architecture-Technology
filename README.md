# Emerging-System-Architecture-Technology
-  Summarize the project and what problem it was solving.
    The projet was to create a thermometer that was connected to a heater, and it solved the problem of a human being having to constantly adjust the heater to keep their room at a desired temperature.  The embedded system within the thermometer will automatically turn the heater off in the case that the current temperature is above the desired temperature and will turn it on whenever the room's temperature is below the desired temperature.

-  What did you do particularly well?
    In this project, I was particularly good at designing the task scheduler and figuring out how to utilize a timer going off every 100ms in order to schedule tasks at 200, 500, and 1000 ms intervals.
    
-  Where could you improve?
    During the setup of the project, there was a confusing error that took a long time to fix.  It was an error of the IDE not being able to find the main function.  I never actually found why the error was popping up, I simply rebuilt the project piece-by-piece, starting from a version of the project that I know would run, and I tested it after every piece was added in attempts at finding the "problem piece".  Such a piece was never found and once the last piece was added, the project worked without error.

-  What tools and/or resources are you adding to your support network?
    The main tool I used for support was google.  Any time I would hit an error or any other obstacle that I didn't immediately know how to overcome, I used google to give me ideas.  
    
-  What skills from this project will be particularly transferable to other projects and/or course work?  
    I can certainly see myself using the skill I develped when trying to find the cause of the "main not found" error by rebuilding the project piece-by-piece.  Even though in this case there was no error found, I still think it is a valuable detective-like skill that I will be making use of more going forward.

-  How did you make this project maintainable, readable, and adaptable?
    When writing the code for this project, I made sure to use a lot of comments.  I also diagramed the structure of the code out using lucidchart before even starting the code process.  Both of those actions go very far in making my code maintainable and readable.  As for being adaptable, nothing is hardcoded and all aspects of each task is consolidated in it's own function.  This will make changing/adding tasks much easier if one wanted to do so in the future.  
