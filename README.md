post_tools
==========

A bunch of tools I wrote to help with my video post-production workflows. Shake well before using, use at your own risk.


* **projectfolders:**

  Shell script that creates skeleton project-folder heirarchies (based on specific workflow) in the current working directory. 
  
  In my workflow, I like to separate different parts of the post-production workflow into their own separate folders (since generally, each task is done by a separate person in our facility, and I prefer to let them have their own "playground" in which they can work in), so this script creates top-level skeleton heirarchies for Color Correction, Offline Editorial and Online Editorial workflows.
  
  So running the tool like this: 
  
  projectfolders color
  
  Creates a skeleton folder heirarchy like this:
  
  ![Example output](http://d.pr/i/1lOO3/3yeM6vY3+)
  
  Edit the mkdir commands in the case statements as necessary for your own specific workflow.

