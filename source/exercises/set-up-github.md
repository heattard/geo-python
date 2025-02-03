# Setting up git and Github

## Task 1 - Make a Github Account
Navigate to [Github.com](github.com). Create a *free* account if you don't already have one. 

## Task 2 - Make a repository to hold all of your homework assignments

A repository (often referred to as "repo") is a centralized location where data, files, or software are stored and managed. This centralized location makes it easy for multiple people to have access to code and the keep track of version history. 

1. Create a new repo by clicking **new**

   * Name the repository *geo-python-exercises*
   * Mark it as **private**
   * Initalize with a README file
   * keep all the other defaults the same

## Exercise 3 - Add me as a collaborator 

After you create your repo in the step above you will be on the main page of your repo. The steps to add a callaborator are below and are from [this page.](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository)

1. Click on **Settings**

2. In the "Access" section on the sidebar, click **Collaborators**

3. Click **Add poeple**

4. In the serach filed, start typing my name or username (given in class) and you will see my picture with my username. Click on me

5. Click **Add *NAME* to *REPOSITORY***

6. I will receive an email inviting me to the repository. Once I accept, I will have access to your repo. This is how I will see your completed exercises. 

## Exercise 4 - Set up SSH with github 
These directions are based on [these github directions to generate a key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) and [these directions to add teh SSH key to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
1. In your terminal past this text: `ssh-keygen -t ed25519 -C "your_email@example.com"`

2. When you are promted to "Enter a file in which to save the key", you can press **Return** to accept the default file location

3. At the prompt, type a secure passphrase **do NOT leave this empty**

4. Copy the SSH public key to your clipboard by copying this into your terminal `more ~/.ssh/id_ed25519.pub` and highlighting and copying the output

5. In the upper-right corner of any page on GitHub click your profile photo, then click **Settings**

6. In the "Access" section of the sideboar, click **SSH and GPG keys**

7. Click **New SSH key** or **Add SSH key**

8. In the "Title" field type "WaC server"

9. For the type of key select "Authentication"

10. In the "Key" field paste the public key you copied from the terminal

    * If there is a line break in your key when you paste, go to the break and hit delete once.  Ask me with questions

12. Click **Add SSH** key

13. If prompted, confirm access to your account on GitHub 

## Exercise 5 - Connect your github repo to the Wac Server 
1. Navigate to your `geo-python` repo

2. In your repo on github, where it says **Code** in green:

   * Select **SSH**
   * Click the button to copy the path 

3. In your termainal type `git clone <link to your repo>` (remove the <>).

   * This copies down everything in your github repo to the local machine to work on
   * It *creates* a local git repository
     
4. Enter your *SSH key pasphrase* when prompted.  This is **different** from your github password

5. Type `git status` and everything should be up to date 

## Exercise 6 - Start with exericse 1 

1. If you already started exericse 1, copy your `exercise-1.ipynb` notebook into this directory
   
2. If you did not start exercise 1, create your `exercise-1.ipynb` notebook in this directory
   
3. Type `git add exercise-1.ipynb` this puts your new notebook into your git repo
   * You must do this every time with a new file

4. Type `git status` - this should say `No commits yet` and list the files that have changes to be commited. These files are said to be `staged` to commit meaning they have changes and are ready to be commited

5. Type `git commit -m "initial commit"`. This will commit all of your changes and include a message

6. At this point if you run `git status` it should say there is nothing to commit, which means that all of your changes and version control are *stored locally*

## Continue to commit your code as you work
As you continue in this exericise you will be making changes to your notebook `Exercise-1.ipynb`. These changes need to be committed, so they are saved in your version control.

To commit a change you will run the same steps repeatedly from the terminal: 
1. `git add <filename>`

2. `git commit -m "short blurb about what changed"`

3. Periodically (**and always before you leave the lab**), you will need to *push* these changes to your online repository. To do this type `git push`

   * Enter your *SSH key pasphrase* when prompted


