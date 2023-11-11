This is a directory of files you can add to any Obsidian vault to add GTD task tracking capabilities. Using this requires the Tasks community plugin.  The Archiver plugin is highly recommended for cleaning up the lists.  Please install both and enable them.  The terminology used below assumes basic familiarity with _Getting Things Done (GTD)_

To use this, add the TODO directory to your vault.  All the queries and functionality ignores the rest of your vault except for the ```_All tasks in daily notes``` page. That will look for a top level folder called "daily notes" for ... tasks in your daily notes. If you keep you daily notes elsewhere, modify the query. If don't use daily notes or don't put quick capture tasks in there ... just delete that file and update ```zNavmenu```

Tour of what's in here
- README - duh
- All the files that start with underscores are the "working pages". These query your "project notes"  in different ways to focus on just what you want to see
	- ByContext- searches for tasks tagged with pre-defined contexts. You'll have to update these for contexts you want to use
	- Future - this pulls out your "someday/maybe" items. Useful for your weekly review
	- NextActions - things you've decided you can work on right now
	- Urgent - things you've marked as the highest priority or reminders that are due or overdue. I usually work off this list
	- Waiting - things you've assigned or asked of others.  Helps you keep from losing track of things. This is useful for your weekly review
- There rest of the files are files dedicated to your projects.  There's a template (see below) that makes all the magic work
- ProjectTemplate - duplicate this to create a new project(rightclick this file > Make a Copy). It's broken down in to 4 headers as described below
	- NextActions - your next actions go here. Mark the most important items as "high" priority using the Tasks plugin and they'll show up in the ```Urgent``` working page
	- Ticklers - anything with a start or due date goes here. Especially useful for recurring items as marking them complete will automatically create a new undone task.
	- Someday - things you could do at some point in the future, but not now. Reviewing this list regularly is important
	- Waiting - If you've done a task regarding asking something from someone or asked someone else to do something for you and are waiting for someone to get back to you , don't mark the task done .. move it here and mark it done when they get back to you. This gets it off your normal working pages and out of your brain. 
- zNavmenu - menu included in the working pages to navigate between them. 

There are two sample project pages to show you how the different working pages work.  I recommend you start wit the ```Urgent``` page and see what's what. 
 
