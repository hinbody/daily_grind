# This is a module to store and track tasks that need to be done

## Overview

This module can be used to store tasks that need to be completed, track the
progress and state of those tasks, and mark them as complete once they are
finished. 

The attributes a task can have are:

1. Title
2. Description
3. Creation Date - automatically created
4. Due Date
5. Assignee - separate object?
    * Name
    * Department(Group)
    * UID
    * email 
    * phone
6. State - todo, in progress, on hold, done
7. Completion date - automatically created when marked as done
8. Notes

## Functions

Create task to be completed

Update task attributes

Change task state - most likely attribute to be changed, should be a shortcut

Return all tasks

Return all tasks belonging to an Assignee

Return all tasks with a particular state

Return all tasks due in a particular date range(including a single date)

Show metrics

* time to complete tasks for group or inidvidual
