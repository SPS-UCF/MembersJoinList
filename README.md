# Members Join List
Adding your name to the file is an easy way to make your first pull request with the organization.

# Introduction

## What is a Pull Request
A pull request (abbreviated as PR) is the ability to request a Git repository administrator to fetch changes you've made to their repository.

The concept is simple: Lisa has a repository of code. Bart would like to help out. Bart creates a copy (what's called a fork) of Lisa's code, makes changes, and submits a pull request to Lisa. She can then decide whether she would like to accept Bart's changes (by pulling the changes from Bart's Git repository - hence the name) or not.

Github provides a comfortable interface to submit pull requests and to accept and merge pull requests. It makes it close to trivial to provide changes and have them easily reviewed and added to an existing code-base.

## Submitting your pull request
Github has an excellent [pull request tutorial](https://help.github.com/articles/using-pull-requests/) which can walk you through anything not covered here. We begin by creating  a repository fork and it's fairly easy to do. When opening the repository on Github, we simply press Fork on the top right.

Once the forking process has finished, Github will host another copy of the repository under our username. However, since it's on the Github server and we don't have access to the server, we actually need to make a local copy on our hard drive. We'll be able to edit it on our computer and sync it with our Github copy.

If you're using the Git command-line application, you can do this using the following command:

    git clone https://github.com/SPS-UCF/MembersJoinList.git

You can also find this path on the right menu between Settings and Download ZIP. It's called clone URL. You can just copy paste it.

## Contributing
Once you've cloned the repository, we have a file set up containing the entire names list. We can simply edit it and commit.

### Commiting
A commit is basically a change with a summary and a possible description.

In order to make a commit, you can either have Git open your editor for you and let you write a commit message, or simply ask Git to commit with a message from the command line without opening an editor.
First, let's add all the files we've edited:

    git add Members_List.txt
    
Now we can commit those:
    
    git commit -m "short description"
    
### Pushing the changes
Now we have our branch ready with our change committed. It has a clear summary and helpful description. We're almost ready to provide this to the author.

A pull request on Github can only be sent from other Github repositories. What we want to do is simply sync our local copy with our Github copy. Then we can submit the pull request.

Doing this is simple enough:

    git push
    
## Cleaning Up
After the push has been made you can now delete the fork you downloaded. The organization manager will recieve the notification about your pull request and will push your changes and send you an invitation to your Github account to become a member.

Congratulations! You're a member of the SPS-UCF Programming Project.
