### We Created an Online Repository on GitHub

This means we created a folder online. Now, we need to clone that folder.

#### To Clone the Repository

To clone the repository, we need to copy its URL and use one of these terminals:

- **PowerShell**
- **Command Prompt (CMD)**

### Useful PowerShell Commands:

- **Change directory into a folder:**
  ```sh
  $ cd foldername
  ```

- **Move back one directory:**
  ```sh
  $ cd ..
  ```

- **List files in the current directory:**
  ```sh
  $ ls  
  $ dir
  ```

- **Create a new folder:**
  ```sh
  $ mkdir foldername
  ```

#### Cloning the Repository
Use the following command to clone the repository:

```sh
$ git clone repository-url
```

Navigate into the cloned repository:

```sh
$ cd repo-name
```

### Authenticating Git with Username and Email

Set your Git username and email (only needed on a new system):

```sh
$ git config --global user.name "muhammadhanzala5656"
$ git config --global user.email "email"
```

If already configured, you don’t need to run this again.

### Removing Origin

Remove the existing remote origin:

```sh
$ git remote remove origin
```

### Adding a New Remote Origin

Add authentication using your token, username, and repository:

```sh
$ git remote add origin https://[TOKEN]@github.com/[REPO-OWNER]/[REPO-NAME]
```

For example:

```sh
$ git remote add origin https://[Token]@github.com/muhammadhanzala5656/abcabc
```

> **Note:** Never share your token publicly!

### Tracking Changes in Git

To track all new or modified files:

```sh
$ git add .
```

To track a specific file:

```sh
$ git add "filename.py"
```

### Committing Changes

After adding files, commit them with a message:

```sh
$ git commit -m "Describe the changes made"
```

This saves the changes locally.

### Pushing Changes to GitHub

To upload changes to the remote repository:

```sh
$ git push origin main
```
