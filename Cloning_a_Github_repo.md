## Creating your GitHub repo from the course template

You will be provided with a link to create your GitHub repo for your assignment. Clicking on the link will bring up an "Accept the assignment" page (you might be asked to log in with your GitHub account).

 <img src="img/class_link_1.png" width="300px" hspace="50"/>

 In this example, the assignmnent name is `Sample`. Each assignment will have a unique name.
 
 Click `Accept this assignment`. This will bring up the following page:

 <img src="img/class_link_2.png" width="300px" hspace="50"/>

The page indicates that your assignment repository ("repo" for short) is being configured. You may need to **refresh** the page to see the link to your personal repo.

<img src="img/class_link_3.png" width="300px" hspace="50"/>

Clicking on the link in the blue box will bring you to your repo page.

<img src="img/class_link_4.png" width="300px" hspace="50"/>

The repo page will normally have a README file with instructions on how to tackle the assignment. But note that you will not create/modify the R scripts on GitHub. Instead, you will clone the repo onto your personal computer (in regular parlance, you will be creating an assignment folder on your PC from the GitHub repo). This is where your local installation of `git` comes into play.

## Copying (cloning) a Github Repo locally to your computer

1. Bring up a git shell on your local computer. On a **Mac**, you will open a **Terminal**.  On **Windows**, you will bring up a **Git shell**.

2. If your Git shell is in a folder other than where you plan to clone the project folder into, navigate to the folder where you will want to copy the new repo to. You can change directory using the `cd` command. For example, if you want to create the repo to your `ES218` folder that resides under your home directory, type the following if you are working on a **Mac**:

   ```{r}
   cd ~/ES218
   ```

   If you are working on a **Windows** PC, type:
   
   ```{r}
   cd ~/Documents/ES218 
   ```    
   The tilde, `~`, is interpreted as you home directory. Alternatively, you could have typed the full directory path to your folder. For example, on a Windows machine, you could have typed:
   
   ```{r}
   cd /c/Users/jdcolby/ES218
   ```  

3. In your web browser, navigate to the Github/repo page you want to clone. (Note that if you are given a link to a **GitHub Classroom** assignment, you will use that link instead and this as well as the next two steps).

4. Click on the *Code* button. This will reveal the full web path to your repo. Copy that full path by either selecting it and copying it, or by clicking on the icon to its right.

   <img src="img/github_repo_link.png" width="500px" hspace="50"/>

> NOTE: Before proceeding, if this is the first time you are cloning from your GitHub account to your local computer, you will need to create and install a token following instructions outlined on [this page](authenticating_with_github.md). **Keep the Token window open!** You will need to copy and paste that token in later steps.

5. In your git shell, clone the repo by typing the link from the Github page. Make sure that the full link is copied (the last element of the link should end with `*.git`). For example, if the link is `https://github.com/Colby-es218-2024/sample-jdcolby.git`, type: 

   ```{r}
   git clone https://github.com/Colby-es218-2024/sample-jdcolby.git
   ```

6. **If this is your first time cloning from your GitHub repo**, you will be asked fro your GitHub user name.

   ```r
   $ git clone https://github.com/Colby-es218-2024/sample-jdcolby.git
   Cloning into 'sample-jdcolby'...
   Username for 'https://github.com':
   ```
   Type your GitHub username and press enter.

   You will then be prompted to enter a paswword. But, this will not be your regular GitHub password. Instead, you will paste the PAT token you created for the machine you are working on.

   Note that for **Windows**, you might be presented with a **GitHub Sign in** window. If so, select the **Token** option.

<img src="img/sign_in_token.png" width="359px" hspace="50"/>

In the Token field, paste the PAT token you created for the machine you are working on.

8. At this point, you have a clone (copy) of the repo content on your computer. 

   <img src="img/local_repo_folder.PNG" width="400px" hspace="50"/>
   
9. You can now work in this folder as you would with any other assigment folder.  When you have completed your assignment, be sure to save all files (R scripts, etc...) before submitting the assignment to GitHub. You can find these instructions on submitting yout assignment [here](stage_and_push.md).
   
   -----

[Back to the home page](index.html)

<div class="footer">
<hr/>
<a rel="license" href="https://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/80x15.png" /></a>  Manny Gimond (2022)
</br>

