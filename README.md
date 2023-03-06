# File_to_GitHub

This repository was homework for the ComIT course. The simulated situation is: I have a local Git repository with one Python file and one remote repository on GitHub; so I need to merge the remote repository with my local one without losing any file or their histories.

To solve this, I did the steps below:

1. Open the *git bash* command line.

2. Create the `helloworld.py` file through the command line using nano.
 
2.1.  Created the local repository and added the helloworld.py using the commands:
  
  a) `git init`

b) `git add .`

c) `git commit -m “message”`

There is no remote repository attached to the local one so, there is no need to: `git push origin main`

3. Create the remote repository "File_to_GitHub" on github.com

4. Returned to the local bash to connect the local repository to the remote one: `git remote add origin "https link"` (from GitHub)

5. Pulled the changes (files) from the remote repository: `git pull origin main --allow-unrelated-histories`

6. To do a final commit with all the files I edited the Python file again so I had something to commit. After the modification I could do:

a) `git add .`

b) `git commit -m "First change in the file"`

And finally: `git push origin main`

In the end, I pushed my file up to the remote repository.
