# Hacktoberfest

## 🚀 Quick Start :

#### Step 1: Forking the repository :

To work on an open-source project, you will first need to make your copy of the repository. To do this, you should fork the repository and then clone it so that you have a local working copy.

Get your own Fork/Copy of repository by clicking `Fork` button right upper corner.<br><br>

#### Step 2: Clone the Forked Repository

After the repository is forked, you can now clone it so that you have a local working copy of the codebase.

To make your local copy of the repository follow the steps:

- Open the Command Prompt
- Type this command:

```bash
$ git clone https://github.com/<your-github-username>/Hacktoberfest-FirstPR
```

#### Step 3: Creating a new branch (IMP)

This is one of the very important step that you should follow to contribute to Open Source. A branch helps to manage the workflow, isolate your code and does not create a mess. To create a new branch:

```bash
$ git branch <name_of_branch>
$ git checkout -b <name_of_branch>
```

Keep your cloned repo up-to date by pulling from upstream (this will also avoid any merge conflicts while committing new changes)

```bash
git pull origin main
```

#### Step 5: Contribute

Make relevant changes according to the issue that you were assigned on. Contribute in any way you feel like :)

#### Step 6: Committing and Pushing

Once you have modified an existing file or added a new file to the project, you can add it to your local repository, which we can do with the git add command.

```bash
git add .
```

With our file staged, we’ll want to record the changes that we made to the repository with the git commit command.

The commit message is an important aspect of your code contribution; it helps the other contributors fully understand the change you have made, why you made it, and how significant it is.

```bash
git commit -m "useful commit message"
```

At this point you can use the git push command to push the changes to the current branch of your forked repository:

```bash
git push origin <branch-name>
```

#### Step 7: Create Pull Request

Now, you are ready to make a pull request to the original repository.

You should navigate to your forked repository, and press the "Compare & pull request" button on the page.

GitHub will alert you that you can merge the two branches because there is no competing code. You should add in a title, a comment, and then press the “Create pull request” button.

## Contribution Guidelines

Please ensure your pull request adheres to the following guidelines:

- Start the name with a capital.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
<br>

### Thanks For Contributing Here 😄