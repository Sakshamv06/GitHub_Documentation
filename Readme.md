# GitHub for Beginners
![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRSNdKSmb4TvaTpyPELqP7Ei2eb3LnWFD_rbw&s)

This  is a documentation of GitHub for the newbies who have no idea of what GitHub is, in this documentation we will start with the basics like what is GitHub and Git, creating an account on GitHub, a hello world exercise to learn Github's pull request workflow, setting up your profile, finding inspiration on GitHub, Downloading files from GitHub, uploading a project to GitHub, git, and GitHub learning resources. **Let's start your journey** 

## Table of content 
1. [About GitHub and Git](#About-GitHub-and-Git)
2. [Creating an account on GitHub](#Creating-an-account-on-GitHub)
3. [Hello World](#Hello-World)
4. [Setting up your profile](#Setting-up-your-Profile)
5. [Finding inspiration on Github](#Finding-inspiration-on-GitHub)
6. [Downloading files from GitHub](#Downloading-files-from-GitHub)
7. [Uploading a project to GitHub](#Uploading-a-project-to-GitHub)
8. [Git and GitHub learning resources](#Git-and-GitHub-learning-resources)


## About GitHub and Git

### About GitHub

**GitHub** is like an online notebook where you can keep your code safe, share it, and work with others.

When you save your code in a "repository" (or repo) on GitHub, you can:

- **Show your work:** Let others see what you've done.
- **Keep track of changes:** See how your code changes over time.
- **Get feedback:** Others can look at your code and suggest ways to make it better.
- **Work together:** You and others can work on the same project without messing up each other's work.

GitHub helps people work together easily by using a special tool called **Git** that helps manage and track code changes.


### About Git

**Git** is a tool that helps you keep track of changes in your files. It's especially helpful when multiple people are working on the same files at the same time.

In a typical Git workflow, you would:

- **Create a branch:** This is like making a copy of the main files where you can work without affecting others.
- **Make changes:** You can edit the files on your branch safely, without worrying about others' work.
- **Merge changes:** Git helps you combine your changes back into the main files without messing up others' updates.
- **Stay updated:** Git keeps track of everyone's changes, so everyone is always working on the latest version of the project.

### How do Git and GitHub work together?

When you upload files to GitHub, you store them in a "Git repository." This means that when you make changes (called "commits") to your files, Git automatically tracks and manages these changes.

You can do many Git-related tasks directly on GitHub using your web browser, like creating a Git repository, making branches, and uploading or editing files.

However, most people prefer to work on their files on their own computers and then sync their changes with the main "remote" repository on GitHub. Tools like GitHub Desktop can help with this.

When you're working with others on the same repository, you will:

- **Pull** the latest changes made by others from the GitHub repository.
- **Push** your own changes back to the GitHub repository.

Git smartly combines everyone's changes, and GitHub helps manage this with features like "pull requests."


## Creating an account on GitHub

To start using GitHub, you need to create a free personal account on GitHub.com and verify your email address.

Everyone who uses GitHub.com has a personal account. This account is your identity on the site and comes with a username and profile.

### How to Sign Up for a Personal Account

1. Go to [GitHub.com](https://github.com/).
2. Click on **Sign up**.
3. Follow the steps to create your personal account.

During sign-up, you'll need to verify your email address. Without this verification, you won’t be able to do some important things on GitHub, like creating a repository.


## Hello World

### Introduction

This tutorial will teach you the basics of GitHub, including how to use repositories, branches, commits, and pull requests. You'll create your own "Hello World" repository and learn how to use GitHub's pull request workflow, a popular way to work on code.

In this guide, you will:

- Create and use a repository.
- Start and manage a new branch.
- Make changes to a file and push them to GitHub as commits.
- Open and merge a pull request.

#### Prerequisites

- You need a GitHub account. If you don't have one, see "Creating an account on GitHub."
- You don't need to know how to code, use the command line, or install Git (the tool GitHub is built on).

#### Step 1: Create a repository

A repository is like a folder that holds related items, such as files, images, and other folders. Usually, a repository groups items that belong to the same project.

Repositories often include a README file that contains information about your project. README files are written in Markdown, which is a simple way to format text. We'll learn more about Markdown in the next tutorial, "[Setting up your profile](#Setting up Your Profile)."

You can add a README file when you create your new repository. GitHub also lets you add a license file and other options, but you can skip them for now.

Your `hello-world` repository can be a place where you store ideas, resources, or share and discuss things with others.

1. In the upper-right corner of any page, click the "+" icon, then click **New repository**.
![image](https://docs.github.com/assets/cb-29762/mw-1440/images/help/repository/repo-create-global-nav-update.webp)

2. In the "Repository name" box, type `hello-world`.

3. In the "Description" box, type a short description, like "This repository is for practicing the GitHub Flow."

4. Choose whether your repository will be Public or Private.

5. Select **Add a README file**.

6. Click **Create repository**.

#### Step 2: Create a branch

Branches let you have different versions of a repository at the same time.

By default, your repository has one branch named `main`, which is considered the main version. You can create more branches from `main` to work on different versions of your project.

Branches are useful when you want to add new features to a project without changing the main version. Work done on different branches won't affect `main` until you merge it.

When you create a branch from `main`, you're making a copy of `main` as it was at that point in time. If someone else updates the `main` branch while you're working on your branch, you can pull in those updates.

This diagram shows:

- The `main` branch.
- A new branch called `feature`.
- The journey that `feature` takes before it's merged into `main`.
![image](https://docs.github.com/assets/cb-23923/mw-1440/images/help/repository/branching.webp)

##### Creating a branch

1. Click the **Code** tab of your `hello-world` repository.

2. Above the file list, click the dropdown menu that says `main`.
![image](https://docs.github.com/assets/cb-16584/mw-1440/images/help/branches/branch-selection-dropdown-global-nav-update.webp)

3. In the text box, type a branch name, like `readme-edits`.

4. Click **Create branch: readme-edits from main**.
![image](https://docs.github.com/assets/cb-31023/mw-1440/images/help/repository/new-branch.webp)

Now you have two branches, `main` and `readme-edits`. Right now, they look exactly the same. Next, you'll add changes to the `readme-edits` branch.

#### Step 3: Make and commit changes

When you created a new branch, GitHub took you to the code page for your new `readme-edits` branch, which is a copy of `main`.

You can make and save changes to the files in your repository. On GitHub, saved changes are called commits. Each commit has a message that explains why the change was made. Commit messages help others understand what you've done and why.

1. Under the `readme-edits` branch, click the `README.md` file.
2. To edit the file, click the pencil icon.
3. In the editor, write a bit about yourself.
4. Click **Commit changes**.
5. In the "Commit changes" box, write a message describing your changes.
6. Click **Commit changes**.

These changes will only affect the `README` file on your `readme-edits` branch, so now this branch is different from `main`.

#### Conclusion

By completing this tutorial, you've learned how to create a project on GitHub.

Here's what you've accomplished:

- Created a repository.
- Started and managed a new branch.
- Made changes to a file and committed them to GitHub.


## Setting up your profile

### About your profile

Your GitHub profile is a place where others can learn more about you. You can use it to:

- Share your interests and skills.
- Showcase your projects and contributions.
- Express your identity and let the GitHub community know who you are.

In this guide, you’ll learn how to personalize your profile by adding a profile picture, bio, and a profile README.

You'll also get an introduction to Markdown syntax, which is used to format text on GitHub.

#### Prerequisites

You need a GitHub account. For details, see "[Creating an account on GitHub](#Creating-an-account-on-GitHub)."

### Adding a profile picture and bio

First, add a picture to your profile. Your profile picture helps others identify you on GitHub.

#### Adding a profile picture

1. In the upper-right corner, click your profile avatar, then click **Settings** from the dropdown menu.
2. Under "Profile Picture," click **Edit**, then **Upload a photo**.
![image](https://docs.github.com/assets/cb-72839/mw-1440/images/help/profile/edit-profile-photo.webp)
3. Select an image and click **Upload**.
4. Crop your picture if needed.
5. Click **Set new profile picture**.

Next, add some basic information about yourself to be shown below your profile picture.

#### Adding a bio

1. On your profile page, click **Edit profile** below your profile picture.
2. In the "Bio" section, write a few sentences about yourself, like who you are and what you do.
3. To add an emoji, visit "[Emoji cheat sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)" and copy an emoji into the "Bio" box.
4. Optionally, add your pronouns, workplace, location, timezone, and links to your personal website and social accounts. Pronouns are visible only to logged-in users.
5. Click **Save**.

#### Adding a profile README

Create a special repository and README file that will be displayed directly on your profile page. This README can include information about your interests, skills, and background.

##### Step 1: Create a new repository for your profile README

1. In the upper-right corner, click **New repository**.
![image](https://docs.github.com/assets/cb-29762/mw-1440/images/help/repository/repo-create-global-nav-update.webp)
2. Name the repository exactly the same as your GitHub username. For example, if your username is "Sakshamv06", the repository name should be "Sakshamv06."
3. Optionally, add a description, like "My personal repository."
4. Choose **Public**.
5. Select **Initialize this repository with a README**.
6. Click **Create repository**.

##### Step 2: Edit the README.md file

1. Click the pencil icon next to your profile README.
![image](https://github.com/Sakshamv06/GitHub_Documentation/blob/main/Screenshot%20from%202024-06-26%2014-55-10.png)
2. In the "Edit" view, delete the text `### Hi there` and type `# About me`.
- In Markdown, `#` creates a large heading, while `###` makes a smaller heading.
3. Toggle to "Preview" to see how the text looks. You should see the new text as a large heading.
4. Toggle back to "Edit."
5. Delete lines 3 and 16.
6. Add details about yourself on lines 8 to 15. You can include interests, skills, hobbies, or a fun fact.
7. Toggle to "Preview" to see how your changes look.
8. Toggle back to "Edit" and remove any unwanted text.
9. Continue customizing your profile README. Use the "[Emoji cheat sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)" for emojis and the "[Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/)" for formatting help.

##### Step 3: Publish your changes

1. When you’re satisfied with the preview, click **Commit changes**.
2. In the dialog box, click **Commit changes** again.
3. Go back to your profile page. Your new profile README will now be visible on your profile.

## Finding Inspiration on GitHub

### Introduction

GitHub is a huge open-source community where you can find interesting repositories, topics, code, people, and organizations to inspire your own work or support your learning. 

Once you find something you like, you can:

- **Star** repositories or topics to save them for later.
- **Follow** people or organizations to get updates on their activities.
- **Download** repositories or code to use and customize.
- **Contribute** to projects by opening a pull request.

Stars and follows will show updates on your personal dashboard.

#### Visit Explore GitHub

1. Go to [Explore GitHub](https://github.com/explore).
2. Browse popular repositories and topics.
3. Click **Star** next to repositories and topics you like to save them.
4. Visit your stars page to see all your starred repositories and topics.

##### Search for a Topic or Project

1. Go to [GitHub Search](https://github.com/search).
2. Enter keywords like "how to build a webpage" or "skills-course" in the search bar.
3. Use the left sidebar to filter results. For instance, to browse all repositories under the "skills-course" topic, search "skills-course" and filter by "Topic".
4. Star the repositories you find interesting.

##### Following People and Organizations

Staying updated on projects and topics is easy by following people and organizations.

###### Following People

1. Go to the user’s profile page.
2. Click **Follow** under their profile picture.
3. To stop following, click **Unfollow**.

###### Following Organizations

1. Visit the organization’s page you want to follow.
2. Click **Follow** in the top-right corner.
![image](https://docs.github.com/assets/cb-32862/mw-1440/images/help/profile/organization-profile-following.webp)
3. To stop following, click **Unfollow**.


## ## Downloading Files from GitHub

### Introduction

GitHub hosts millions of open-source projects. You can get copies of these projects in different ways depending on what you need:

- **Download** a snapshot of files as a zip if you just need to use or customize them without version control.
- **Clone** a repository to your local computer if you want to work with the files and use Git to track changes and sync them.
- **Fork** a repository to create a new project on GitHub based on the original, useful for contributing or creating your own version.

This guide focuses on downloading a repository’s files to your local computer without using Git.

#### Prerequisites

- You need a GitHub account.

### Downloading a Repository

1. Go to the repository you want to download.

2. Click **Code** above the file list.
![image](https://docs.github.com/assets/cb-13128/mw-1440/images/help/repository/code-button.webp)

3. Click **Download ZIP**.

### Cloning a Repository

1. Go to the main page of the repository on GitHub.

2. Click **Code** above the file list.
![image](https://docs.github.com/assets/cb-13128/mw-1440/images/help/repository/code-button.webp)

3. Copy the URL for the repository:
   - For HTTPS, click **HTTPS** and copy the URL.
   - For SSH, click **SSH** and copy the URL.
   - For GitHub CLI, click **GitHub CLI** and copy the URL.
![image](https://docs.github.com/assets/cb-60499/mw-1440/images/help/repository/https-url-clone-cli.webp)

4. Open Terminal.

5. Change to the directory where you want to save the repository.

6. Type `git clone`, then paste the URL you copied.


## Uploading a Project to GitHub

### Introduction

This tutorial will guide you through the process of uploading a group of files to a GitHub repository. Uploading your files to GitHub allows you to:

- **Apply version control** to manage and protect your project's history.
- **Back up your work** with cloud storage.
- **Pin the repository** to your profile for visibility.
- **Share and discuss** your project publicly or privately.

#### Prerequisites

- A GitHub account.
- A group of files you'd like to upload.

### Step 1: Create a New Repository

1. In the upper-right corner of any page, click the **+** icon, then select **New repository**.
   ![Image](https://docs.github.com/assets/cb-29762/mw-1440/images/help/repository/repo-create-global-nav-update.webp)

2. Enter a **Repository name** (e.g., "my-first-project").

3. Add a **Description** (e.g., "This is my first project on GitHub").

4. Choose **Public** or **Private**. Select "Public" if you want others to see your project.

5. Check **Add a README file**. This will create a README file that you can edit later.

6. Click **Create repository**.

### Step 2: Upload Files

1. To the right of the page, click the **Add file** dropdown menu, then select **Upload files**.

2. Drag and drop your files and folders into the browser window.

3. At the bottom of the page, under **Commit changes**, select "Commit directly to the main branch", then click **Commit changes**.

### Step 3: Edit the README File

1. From the list of files, click `README.md` to view the file.

2. In the upper-right corner of the file view, click the pencil icon to open the file editor.

3. Replace existing text with a title and description for your project.

4. Click **Preview** to see how it will look. If needed, adjust the text and preview again.

5. Click **Commit changes** to save your updates. 

6. In the dialog box, a commit message will be pre-filled ("Update README.md"). Leave the options as they are and click **Commit changes**.

### Conclusion

You have created a new repository, uploaded files, and updated the README. 

- **Public Repositories**: Visible to everyone and can be shared easily.
- **Private Repositories**: Only visible to you and collaborators you invite.

GitHub tracks changes ("commits") to manage your project's history. You can create new branches from the `main` branch to experiment with changes, then open a pull request to merge those changes back into the `main` branch. For more details, see "[Hello World](#Hello-world)."

## Git and GitHub Learning Resources

### Using GitHub

Enhance your understanding of GitHub with these resources:

- **[GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow)**: Review the fundamentals of a GitHub workflow to manage your project efficiently.
- **[Connecting to GitHub](https://docs.github.com/en/get-started/using-github/connecting-to-github)**: Learn about the various tools for working with GitHub repositories and how to choose the right tool for your needs.
- **[Communicating on GitHub](https://docs.github.com/en/get-started/using-github/communicating-on-github)**: Understand the different communication tools on GitHub, including Issues, Discussions, and pull requests.

### Using Git

Familiarize yourself with Git through these articles:

- **[Getting Started with Git](https://docs.github.com/en/get-started/getting-started-with-git)**: An introduction to the basics of Git.
- **[Using Git](https://docs.github.com/en/get-started/using-git)**: Learn more about Git commands and advanced features.

Additional online resources for learning Git:

- **[Official Git Project Site](https://git-scm.com/)**: The official site for Git with documentation and resources.
- **[ProGit Book](https://git-scm.com/book/en/v2)**: A comprehensive book on Git available for free online.
- **[Git Command List](https://git-scm.com/docs)**: A reference list of Git commands and their usage.

### Online Courses

- **[GitHub Skills](https://skills.github.com/)**: Offers free interactive courses on GitHub with instant feedback, including how to open a pull request, make your first open source contribution, and more.
- **[Git Branching](https://learngitbranching.js.org/)**: A free interactive tool for learning and practicing Git concepts.
- **[Git Course on Pluralsight](https://www.pluralsight.com/courses/code-school-git-real)**: An interactive online course from Pluralsight that covers the basics of Git.

These resources should help you deepen your knowledge of Git and GitHub and improve your workflow management skills.
### Community

Engage with developers globally and get support from GitHub staff by participating in the GitHub Community. You can ask questions, share knowledge, and connect with others in the following way:

- **[GitHub Community Support](https://github.com/orgs/community/discussions/)**: Join discussions to get answers, offer help, and interact with other GitHub users and staff.
