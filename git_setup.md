## Installing git

For **Windows**, download and install git from https://gitforwindows.org/. Go with the default settings. 

For **Macs**, install Git from  http://git-scm.com/downloads. Go with the default settings. 

## Configuring git

You only need to follow this step once on your machine. This step adds your contact information that will be used when uploading (**pushing**) your project folder to Github.

Bring up the git shell (this may be listed as the **Git Bash** application on **Windows** and it may be accessed via your **Terminal** application on the **Mac**). You can also access the shell from inside **RStudio** by clicking on the **Terminal** tab in the lower left-hand pane. Type the following while replacing `Jane Doe` with your name and `jdoe@colby.edu` with your email address.

```{r}
git config --global user.name 'Jane Doe'
git config --global user.email 'jdoe@colby.edu'
```

To check your settings, type:

```{r}
git config --global --list
```

-----

[Back to the home page](index.html)

<div class="footer">
<hr/>
<a rel="license" href="https://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/80x15.png" /></a>  Manny Gimond (2022)
</br>
