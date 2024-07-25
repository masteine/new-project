# Setting Up a New Git Repository and Creating a Development Branch

Follow these instructions to set up a new GitHub repository for 'new-project' and create a development branch to work on new features without affecting the main branch.

## Prerequisites
Ensure you have Git installed on your machine.
Make sure you have a GitHub account.
Step-by-Step Instructions

### 1. Create a New Directory
- 1.1. Open your terminal or command prompt.

- 1.2. Create a new directory named "new-project":

```sh
mkdir new-project
```
- 1.3. Navigate to the "new-project" directory:

```sh
cd new-project
```
### 2. Initialize a New Git Repository

- 2.1. Initialize a new public Git repository inside the "new-project" directory:

```sh
git init --initial-branch=main
```
### 3. Create and Add Initial Content to README.md

- 3.1. Create a new file named README.md:

```sh
touch README.md
```
- 3.2. Open README.md in your preferred text editor and add some initial text.

### 4. Prepare and Commit README.md

- 4.1. Add the README.md file to the staging area:

```sh
git add README.md
```
- 4.2. Commit the changes with the message "init":

```sh
git commit -m "init"
```
### 5. Create and Switch to the Development Branch

- 5.1. Create a new branch named "development" and switch to it:

```sh
git checkout -b development
```
### 6. Update README.md with Instructions

- 6.1. Add these instructions to the README.md file.

### 7. Prepare and Commit Changes in the Development Branch

- 7.1. Add the changes to the staging area:

```sh
git add README.md
```
- 7.2. Commit the changes with a descriptive message:

```sh
git commit -m "Add step-by-step instructions to README.md"
```
### 8. Merge Changes from Development Branch into Main Branch

- 8.1. Switch to the main branch:

```sh
git checkout main
```
- 8.2. Merge the development branch into the main branch:

```sh
git merge development
```
### 9. Check Status and Commit

- 9.1. Check the status to ensure everything is up to date:

```sh
git status
```
- 9.2. If there are any changes, add and commit them:

```sh
git add .
git commit -m "Final commit after merge"
```