# BIT Deoghar Hacktoberfest Contributions :office:

It's always hard the first time you do something. Especially when you are collaborating, making mistakes isn't a comfortable thing. We wanted to simplify the way new open-source contributors learn & contribute for the first time.
This repo will take you from the very scratch to fianlly contributing to the open source.


## Steps to follow :fast_forward:

### 1. Fork it :fork_and_knife:

You can get your own fork/copy of [Hacktoberfest](https://github.com/codesocbitd/Hacktoberfest) by using the <a href="https://github.com/codesocbitd/Hacktoberfest/new/master?readme=1#fork-destination-box"><kbd><b>Fork</b></kbd></a> button or clicking [this](https://github.com/codesocbitd/Hacktoberfest/new/master?readme=1#fork-destination-box) at top-right of your screen.

 [![Fork Button](https://help.github.com/assets/images/help/repository/fork_button.jpg)](https://github.com/greyhatlinux/BITMcontributions/)


### 2. Clone it :busts_in_silhouette:

`NOTE: commands are to be exceuted on Linux, Mac and Windows(using Git Bash)`

You need to clone (download) it to local machine using

```sh
$ git clone https://github.com/codesocbitd/Hacktoberfest.git
```

> This makes a local copy of repository in your machine.

Once you have cloned the `codesocbitd` repository in Github, move to that folder first using change directory command on Linux, Mac and Windows(powershell to be used).

```sh
# This will change directory to a folder Hacktoberfest
$ cd Hacktoberfest
```

Move to this folder for all other commands.

### 3. Set it up :arrow_up:

Run the following commands to see that *your local copy* has a reference to *your forked remote repository* in Github :octocat:

```sh
$ git remote -v
origin  https://github.com/Your_Username/BITMcontributions.git (fetch)
origin  https://github.com/Your_Username/BITMcontributions.git (push)
```

Now, lets add a reference to the original BITMcontributions](https://github.com/greyhatlinux/BITMcontributions/) repository using

```sh
$ git remote add upstream https://github.com/greyhatlinux/BITMcontributions.git
```

> This adds a new remote named ***upstream***.

See the changes using

```sh
$ git remote -v
origin    https://github.com/Your_Username/BITMcontributions.git(fetch)
origin    https://github.com/Your_Username/BITMcontributions.git (push)
```
`In your ase you will see`
```sh
$ git remote -V
upstream  https://github.com/greyhatlinux/BITMcontributions.git (fetch)
upstream  https://github.com/greyhatlinux/BITMcontributions.git (push)
```

### 5. Ready Steady Go... :turtle: :rabbit2:

Once you have completed these steps, you are ready to start contributing by checking our `Help Wanted` Issues and creating [pull requests](https://github.com/greyhatlinux/BITMcontributions/pulls).

### 6. Create a new branch :bangbang:

Whenever you are going to make contribution. Please create seperate branch using command and keep your `master` branch clean (i.e. synced with remote branch).

```sh
# It will create a new branch with name Branch_Name and switch to branch Folder_Name
$ git checkout -b contributor
```

Create a seperate branch for contibution and try to use same name of branch as of folder.

Add your contribution and save in the editor.

To add the changes to the branch. Use

```sh
# To add all files to branch Folder_Name
$ git add .
```

Type in a message relevant for the code reveiwer using

```sh
# This message get associated with all files you have changed
$ git commit -m 'relevant message'
```

Now, Push your awesome work to your remote repository using

```sh
# To push your work to your remote repository
$ git push -u origin contributor
```

Finally, go to your repository in browser and click on `compare and pull requests`.
Then add a title and description to your pull request that explains your precious efforts.



## What to contribute :question:

After making a branch with your username, checkout your branch.

Open the file called index.html and add the following changes after following the instructions in class.

Format : 
```md
<tr>
<td>Swapnil Sinha</td>  //Name
<td>BTECH/60014/18</td>  //Roll
<td>CSE</td>             //Branch
<td>reach_swapnil@outlook.com</td>  //Email
</tr>


```
