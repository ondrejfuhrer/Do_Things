# Do Things

An Alfred Workflow for controlling [Things.app](https://culturedcode.com/things/)

***

## The Commands

So far, Do can only do following things:

1. Add a new task to the Inbox or "Today" lists
2. List and completed the tasks in the inbox and "Today" lists
3. List your projects and the items in them
4. Log your completed tasks
5. Empty the trash

### The Inbox

To list the tasks to the inbox, the command is

    do inbox
    
Alfred will display the items in the inbox, and if you action one of them, it will mark the item as completed.

To add an item to the inbox, just keep typing! For example, the command

    do inbox example task
    
will add a task named "example task" to the inbox.

Please note that the option to add a new item to the list appears among the items in the list. I will be looking into solving this issue in the very near future.

### The "Today" List

The "Today" list works just like the "inbox" ones, just substitute "inbox" for "today", like this

    do today
    
or this

    do today example task
    
### Working with Projects

To access a list of projects, the command is

    do projects
    
When you action one of those options (which will appear in the dropbown), it will display the list of tasks for that list.

### Logging Tasks

To log the completed tasks, the command is

    do log

### Emptying the Trash

To empty the trash, the command is

    do empty

### Adding a Todo from Mac Mail

Select message in Mac Mail.  Alfred will add a todo to things with the title of the of the selected email.  It will add the tags email and the account the email was received.  It will also add a link back to the message.  The title of the link will be `the sender of the message | the message title`.  The command is 

	do mail

### Special characters

Currently Do supports following special characters (modifiators):

1. "#" for adding a tag (i.e. "do today example task #Home" will add "example task" to "Today" list with "Home" tag) 

*** 
## Contact Information

If you want to get a hold of me, feel free to contact me on Twitter: [@alexlafroscia](https://twitter.com/AlexLaFroscia).  I'd love to get some feedback, positive or negative, as well as suggestions and tips on improving Do!
