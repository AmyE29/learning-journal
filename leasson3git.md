# What is git?
Get is a device version control system (DVCS), which is known as the "stupid content tracker". It allows you to make changes in your code while keeping a history of those changes for you. This history tracking lets you view that changes that you have made, apply the changes, and if needed roll back the changes to a previous version. It also allows you to keep all your files in one repository, instead in multiple revised repositories. This allows multiple developers the ability to work on the code at the same time, with all of them uploading their changes to the same repo.

## Storing your code on GitHub
Github is a place to store your code in the cloud. The cloud is just a server, that allows to to add and retireve content.

*To get your code off of Github to work on it in your terminal you use the command*

    git clone 'https://url/'

You are then able to open the file you want to work on in Visual Studio by typing

    open .
 
In VS you make the changes you want to, and then when you're done go back to the Terminal and type to stage your changes

    git add (filename)

After making your changes you will want to save it by

    git commit -m "put the changes up made in the file"

And then up load it to GitHub

    git push origin master

Now your latest version is stored on GitHub :muscle:

The motto of git is ACP = Add Commit Push!
