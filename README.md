<h1><u></u>Task Manager App</h1></u>

<p><b>The Task Manager App</b> is a basic program, coded in Python, which allows a User to manage their task lists in one place.</p>

<p>For clear organization, each task added must have a <i>category</i> (work, personal, or other), a <i>due date</i>, and a <i>priority</i> (low, medium, or high.)
  Optionally, a task may also include a <i>recurrence</i> level (daily, weekly, or monthly), which will refresh its status to the appropriate level after it's completed.
  Existing tasks may also be listed as <i>dependent</i> tasks when a new one is added, which will prevent the main task from being checked-off until the others are done.</p>

<p>To manage urgency, any overdue tasks will show on launch as <i>Priority Notifications</i>, and tasks due soon will show, as well.
  There is also an <i>Overdue Task Summary</i> option on the main menu. In case of any changes that may effect a task's urgency after adding it, a task's priority level
  can be adjusted at any time after adding it via the menu option, <i>Adjust Task Priorities</i>. </p>

<p>Tasks can be viewed in several different ways. The main option is to view all of them by due date, but <i>Advanced Search</i> and <i>Simple Search</i> features allow
  for a User to search them by keyword, completion status, priority level, category, or due date. <i>Advanced Search</i> includes a combination search for priority, category,
  and/or date. </p>

<p>Tasks can be marked as either completed or deleted at any time via the main menu. When completed, then they will fill the progress bar, and certain awards can be granted
  after reaching certain milestones: bronze, silver, gold, and a special "high-performer" award for a high value task over 50 points. If tasks are deleted, or a backup/import is
  loaded, then the bar and rewards will be altered on relaunch.</p>

<p>Tasks are saved in a JSON file format, task lists can be backed up, and backups can be restored. Tasks can also be imported or exported in CSV format.
  To help a User to remember their most important tasks, <i>Priority Notifications</i> can also be exported as txt files.</p>
