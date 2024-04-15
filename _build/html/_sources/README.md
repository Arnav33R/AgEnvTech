# AgEnvTech at UC Davis
Exploring the intersection of technology and agriculture

Welcome to AgEnvTech at UC Davis, where we delve into the exciting world where agriculture meets technology. This website contains information about the TAE 30 class offered at UC Davis, titled "Mobile Communication & Computing Technologies for Agriculture & the Environment"

## Cloning a Repository, Editing Files, and Pushing Changes

In this tutorial, we'll cover the basic steps for cloning this repository, editing files within it, and then pushing those changes back to the repository and publishing to the website. This project makes use of Jupyter Books, more information about which can be found [here](https://jupyterbook.org/)

### Prerequisites

Before we begin, ensure you have the following:

- Git installed on your system.
- Access to a GitHub account (or any other Git hosting service).

### Step 1: Clone the Repository

To clone a repository, open your terminal or command prompt and navigate to the directory where you want to clone the repository. Then, use the `git clone` command followed by the repository URL. You can find the repository URL as shown in the image below: 

Make sure to do this in the directory you want the repository to reside in. Replace <repository_url> with the actual URL of the repository you want to clone. 

```bash
git clone <repository_url>
```

### Step 2: Navigate to the Repository Directory

Once the repository is cloned, navigate into the directory by using the `cd` command.

```bash
cd <repository_name>
```

This repository name is the same as the one shown on GitHub.

### Step 3: Edit Files and Building Jupyter Book

Now that you're inside the repository directory, you can edit files using any text editor or IDE of your choice. For Jupyter Books, you'll primarily work with Markdown files (.md) and Jupyter Notebooks (.ipynb). You can open the directory using, say, VSCode. 

After you've edited the files, on command line, run the following command from the parent directory of the repository. For example, if my repository path is `\Downloads/AgEnvTech`, I would run this command in the `\Downloads\` directory:

```bash
jupyter-book build <repository_name>/
```
This would build the Jupyter Book, allowing you to view the contents. Typically, in the command line, it will give you the file path to enter in your browser to direct you to the website. You can paste this directly into the browser. 

### Making Changes to the Repository

Once you are ready to push changes to the repository, make sure to run the following commands from the repository directory on your command line:

First, make sure you are in sync with the repository. It is best practice to regularly pull from the repository. Before making any pushes, make sure to run this command

```bash
git pull
```

```bash
git add *
```
This command adds all modified files to the staging area. If you want to add specific files, replace `*` with the file names.

```bash
git commit -m <your_commit_message>
```
Replace <your_commit_message> with a descriptive message for your changes. 

```bash
git push
```
Finally, push your changes back to the repository using the git push command.

If it's your first time pushing to the repository, you may need to set the upstream branch using the following command:

```bash
git push -u origin master
```
Replace `master` with the branch name if you're working on a different branch.

### Publishing Changes to the Website

Once you have pushed all your local changes to the repository, you can run this command on your command line for the Jupyter Book build that will rebuild and republish the website hosted by GitHub Pages:

Make sure to run this from within the repository directory

```bash
ghp-import -n -p -f _build/html
```

### Conclusion and Remarks

Thanks! More help with GitHub development can be found [here](https://github.com/git-guides) and help with Jupyter Book development can be found [here](https://jupyterbook.org/en/stable/intro.html). 

This website was developed by Arnav Rastogi, an undergraduate student at UC Davis, with supervision from Dr. Ali Moghimi. 

