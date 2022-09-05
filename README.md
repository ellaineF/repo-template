# HOW TO USE THIS REPOSITORY

**For Building on this Repo**
1. Fork this repository
2. Clone to your device
3. Build your project into this folder


**For using this repo's contents**

1. Go to .gitconfig file and copy all contents
2. Go to your existing repository and run:

    `git config --global --edit`

    _This will open the config file_

3. Paste all copied contents under alias and Save

## BUILDING A REACT-APP INTO THIS FOLDER

**Building a React App with JS as Default**
`npx create-react-app .`

**Building a React App with TS**
`npx create-react-app . --template -typescript`

# HOW TO USE THE ALIASES

Open terminal
Run:
`git <aliasname>` 
use this as a template

    
`git st`
this is an example - where **st** is the alias for status

# HOW TO ADD MORE ALIASES

Open your terminal and run:
`git config --global alias.<alias-name> "actual command"` 
use this as a template

`git config --global alias.st status` 
this is an example

# HOW TO CONFIGURE USERNAME AND EMAIL

In a similar way above, we run:
`git config --global user.name "Your Name"`

 For email

`git config --global user.email "Your Email"`

### NOTE

1. This Repo is meant for reusing as a template with an already set File Structure and .gitconfig file

2. For more info on what each folder is meant for and file structuring:

Resources used:

- [In-depth Guide to ReactJs Project Structure](https://www.xenonstack.com/insights/reactjs-project-structure)
- [File Structure](https://reactjs.org/docs/faq-structure.html)
- [React Folder Structure in 5 steps [2022]](https://www.robinwieruch.de/react-folder-structure/)