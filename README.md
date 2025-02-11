# Git and Github Tutorial (Credit to Radwan Albahrani!)

This tutorial was originally made by [Radwan Albahrani](https://github.com/Radwan-Albahrani). I've copied it and removed the segments on branching and beyond to keep it simple. This abridged tutorial only covers what you need to know to **submit tasks for the GDG Game Development Bootcamp**.

## Overview

This tutorial will guide you through the process of setting up your development environment and contributing to a project on GitHub.

## Learning Objectives

- Understand the basics of Git and GitHub.
- Learn how to clone a repository.
- Learn how to add changes to a repository.
- Learn how to commit changes to a repository.
- Learn how to push changes to a repository.
- Learn how to create a pull request.

## Resources

- [Git and Github](https://www.youtube.com/watch?v=tRZGeaHPoaw)
- [Git Tutorial (w3schools.com)](https://www.w3schools.com/git/default.asp)
- [How to Use Git and GitHub – Introduction for Beginners (freecodecamp.org)](https://www.freecodecamp.org/news/introduction-to-git-and-github/)
- [Learn Git Branching](https://learngitbranching.js.org/) (Interactive tutorial)
- [Git - Basic Branching and Merging (git-scm.com)](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
- [Pull Requests in VS Code - YouTube](https://www.youtube.com/watch?v=LdSwWxVzUpo)

## Setup and Installation

### 1. Setup

#### 1.1. Install Git (Windows Users Only)

- [Download Git](https://git-scm.com/downloads)

#### 1.2. Install VS Code

- [Download VS Code](https://code.visualstudio.com/download)

#### 1.3 Fork the repository

- Fork the repository by clicking the fork button on the top right corner of the repository page.
  - Click the fork Button

  ![Image of forking the repository](./readme/image.png)

  - Name the repo and click "Create fork"
  ![Alt text](/readme/image25.png)

  - You should now have a copy of the repository on your own account.
  ![Alt text](/readme/image26.png)

### Tutorial

#### 2.1. Git and GitHub

This section will guide you through the process of cloning a repository, adding changes, committing changes, pushing changes, and creating a pull request.

#### 2.1.0. Configure Git

- Open the terminal and run the following commands to configure Git:

```bash
git config --global user.name "<your-name>"
git config --global user.email "<your-email>"
```

These commands will set your name and email for Git. This information will be used to identify you as the author of the changes you make.

Example:

```bash
git config --global user.name "John Doe"
git config --global user.email "JohnDoe@gmail.com"
```

##### 2.1.1. Clone the repository

- Open the terminal and navigate to the directory (also known as folder) where you want to clone the repository.
  - Make sure the path you choose has NO ARABIC LETTERS. This will cause errors.
    - On Mac:
  ![Alt text](/readme/image17.png)
    - On Windows:
  ![Alt text](/readme/image20.png)
- Go to the repository page on **your own account** and click on the green code button.
- Copy the link under the clone section.
![Image of github](/readme/image1.png)
- Run the following command inside of the opened terminal to clone the repository:

```bash
git clone <The Link from your Repository>
```

Example:

```bash
git clone https://github.com/YOUR_NAME/Selection-Project.git
```

![Alt text](./readme/image3.png)

##### 2.1.2. Add changes

- Open the repository directory in VS Code.
  - The path must be INSIDE the cloned repository.
  - Click on File -> Open folder
  ![Alt text](/readme/image21.png)
  - Select the repository folder.
  ![Alt text](/readme/image22.png)
  - The repository should be opened in VS Code.
  ![Alt text](/readme/image18.png)
  - To make sure, run the following command in the terminal INSIDE Vscode:

  ```bash
  git status
  ```

  - The output should be similar to the following:
  ![Alt text](/readme/image19.png)

- Run the following command to add the changes:

```bash
git add .
```

##### 2.1.3. Commit changes

- Run the following command to commit the changes:

```bash
git commit -m "<commit-message>"
```

##### 2.1.4. Push changes

- Run the following command to push the changes:

```bash
git push
```

![Alt text](/readme/image6.png)

##### 2.1.5. Create a pull request

- Go to the repository page and click on the pull request button.
![Alt text](/readme/image7.png)
- Click on the new pull request button.
![Alt text](/readme/image8.png)
- Select the branch you want to merge into the main branch.
![Alt text](/readme/image9.png)
- Click on the create pull request button.
![Alt text](/readme/image10.png)
- Add a title and description for the pull request. Title should be in the following format: `<your-name> - <project-name>`.
![Alt text](/readme/image11.png)
- Click on the create pull request button.
![Alt text](/readme/image12.png)


## Conclusion

This tutorial has covered the basics of Git and GitHub enough for you to start submitting your tasks. You should now be able to clone a repository, add changes, commit changes, push changes, and create a pull request.
