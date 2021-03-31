# How to contribute to this project

This project aims to simplify and guide the way you make your contribution. Please follow the steps below.

From [firstcontributions](https://github.com/firstcontributions/first-contributions)

## Structure of this proyect

### README.md
This is the index, like a Table of Contents.
Add you index into the Table of Contents just 2 lines before the line separator before "How to contribute to this project" section
```
-----------------------------------------
```
You need to add:
* The Title in H2 format or double Hashtag.
* An image that represents the content you want to add. Upload the image inside resources/images folder. Reference that images using html img tag and relative reference
```
<img src="resources/images/YOUR-IMAGE.XYZ" align="left"  width="200" />
```
* Introduction to the content you want to add. It's an introduction don't add more than 500 words unless your images requires to fit well.

### Content
Upload your content file with md extention and [Markdown](https://guides.github.com/features/mastering-markdown/) format inside resources/docs folder. 
You need to add:
* The Title in H1 format or one Hashtag.
* An image that represents the content you want to add. Upload the image inside resources/images folder. Reference that images using html img tag and relative reference
```
<img src="../images/YOUR-IMAGE.XYZ" align="left"  width="200" />
```
* Introduction to the content you want to add. 
* The references of your content. From [Name of The Page](#)
* The content in [Markdown](https://guides.github.com/features/mastering-markdown/) 

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/software-development-practices-and-principles.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the software-development-practices-and-principles repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd software-development-practices-and-principles
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-uncle-bob
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `CONTRIBUTING.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add CONTRIBUTING.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.



