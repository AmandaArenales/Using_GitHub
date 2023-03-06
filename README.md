# Using GitHub

This repository was homework for the ComIT course. The simulated situation is: I need to creat in a local Git repository one Python file and one remote repository on GitHub; then I need to merge the remote repository with my local one without losing any file or their histories.

To solve this, I did the steps below:

1. Open the *git bash* command line.
2. Create the `helloworld.py` file through the command line using nano.
3. Created the local repository and added the helloworld.py using the commands:
     1. `git init`
     2. `git add .`
     3. `git commit -m “message”`

There is no remote repository attached to the local one so, there is no need to: `git push origin main`

4. Create the remote repository *Using GitHub* on github.com

5. Returned to the local bash to connect the local repository to the remote one: `git remote add origin "https link"` (from GitHub)

6. Pulled the changes (files) from the remote repository: `git pull origin main --allow-unrelated-histories`

7. To do a final commit with all the files I edited the Python file again so I had something to commit. After the modification I could do:
    
    1.  `git add .`
    
    2.  `git commit -m "First change in the file"`

And finally: `git push origin main`

In the end, I pushed my file up to the remote repository.
