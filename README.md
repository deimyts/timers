
#Setup Notes
*things to include/look for in a generator
 - change 'title' variable in index.js
 - install nodemon & livereload
 - add gulp/grunt?
 - add bower?

#Spec Notes

*list of basic functions to help with writing tests*
 
##Timeboxing Features
- save a variety of pomodoro style work/break timers with different values.
- create new timers.
- keep a record of pomodoros & other timeboxes completed, organized by date.
- create a one-off work/break timer, and run it without saving it.
- chain timers
- notify user when a timer has gone off.

##Todo Features
- recurring tasks, if not completed on the day they assigned, should be removed from the task queue. A record should be kept that the task was not completed.
- Any task may have its own subtasks.
- Tasks should be kept in a master list which is not visible in the main view.
- default view is daily.
- tasks can be dragged from master list to the daily view. 
- tasks in the daily view do not persist to the next day by default, but can be toggled to do so.

##Overlapping features 
- associate timers with todo tasks.
- keep a record of timeboxes completed for a given todo task.
- display completed task data in a useful and attractive format.


##Startup
$ DEBUG=myapp npm start
