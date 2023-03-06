# Using GitHub

This repository was homework for the ComIT course. The simulated situation is: I have to create a Python file and add it to a local Git repository. After that I have to create a remote repository on GitHub and then connect them both in order to send code to GitHub.

To solve this, I did the steps below:

1. Open the *git bash* command line.
2. Create the [`helloworld.py`](https://github.com/AmandaArenales/File_to_GitHub/blob/main/helloworld.py) file through the command line using nano.
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
