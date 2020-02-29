This folder contains the config files for the "your_machine" game which we build
in our Step-by-Step tutorial which is available from the MPF documentation
site:

http://docs.missionpinball.org/

(Click the "Tutorial" in the menu on the left.)

Each step in the tutorial corresponds to a subfolder in this tutorial folder.
For example, to run the machine from Step 2 in the tutorial, you would open
a command prompt to the step_2 folder. For example:

   C:\mpf-examples\tutorial\step_2>

From there you can run "mpf" (or whatever else you're supposed to do in the tutorial
step).

Each of these steps also contains unit tests which you can run like this:

   C:\mpf-examples\tutorial\step_2>python -m unittest

Note that if you have both Python 2 and 3 installed, you'll need to use "python3" instead of
"python" in the command above.

A tutorial for these unit tests is available in the "Writing Tests" section of the developer
documentation which is here:

http://developer.missionpinball.org
