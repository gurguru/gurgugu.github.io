# Notes for editing the webpage

## Viewing the live webpage

This webpage is currently hosted at: <https://gurguru.github.io>

## Installing needed stuff

### Gitkraken git client

[Download link](https://www.gitkraken.com/)

Git is a version control system with much more features than we use here.

Download, install. On the first run, you get a short tutorial.
Just click through it.
Then log in to github at `settings-> authentication -> github`. This will do a popup or something, just follow the instructions there.

On the __default screen__ go to the folder icon on the `top-left -> clone -> github`. Then select this repository and set the download path. This should be woking now.

### Atom text editor

[Download link](https://atom.io/)

A nice upgrade to the plain old notepad.

Download, install. After add the repository directory with `file-> Add project folder`. Now you can edit things.

## Workflow

### Modifying and testing locally

Open `index.html` with a web browser to see the current local version of the page. If you changed things, you should reload the page with `ctrl+F5`

If you want to change things there is __only__ two files you should edit. `index.html` and `css/freelancer.css`. If you touch the __others__ you will probably __mess up things__.

### Uploading to the live version

So the changes you've made on the webpage are not saved to the version control system yet.

 So we do that. In the GitKraken, on the right side you see 2 lists, and some text boxes.

 The first list aka. __Unstaged changes__ lists the changes that are not set up to be saved to the version control system.

 The second list __Staged changes__ lists the changes that are set up to be saved to the version control system.

  After you selected the files you want to add, you write something about what changes you made to the textboxes then press `Commit`. That updates the local copy of the version control repository.

  To update the live version you need to `Push` to the online repository.
  In GitKraken that is on the top menu.
  The first time you do it, it asks for an __upstream branch__. Just type in the following: `origin/master`.
  Now it should be working fine, and if you load the online webpage, you see the changes madate to it.

  ## Documentation to be added

  ### Upload to online version control without changing the live webpage
