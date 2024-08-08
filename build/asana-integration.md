# Asana integration

## How the date is set in DoubleLoop for Asana tasks

* If there is a start date set in Asana for a task, that will determine the "Happened at" date in DoubleLoop.
* Otherwise:
  * If there is a due date set in Asana for a task, the "end" of the time range is used as the "Happened at" date in DoubleLoop.
  * Otherwise, the "Happened at" date in DoubleLoop is set to the date the Asana task was last modified.

## How the status is set in DoubleLoop for Asana tasks

* If the task is completed in Asana, it's status is set to "Finished" in DoubleLoop.
* Otherwise:
  * If the task does not have a start date in Asana or the start date is in the future, then the status is set to "Not Started"
  * If the tasks has a start date in the past, the status in DoubleLoop is set to "Started."

