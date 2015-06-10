#Quick Start
This article is for people who want to use projects, but not necessarily contribute. If you would like to contribute to Catalyst or a project, see the [Contributing](Contributing.md) page.

To download projects, you will need [Git](https://git-scm.com/downloads) installed. To interact with Git, you will need a shell terminal. If you're on Windows, Git comes with Git Bash.

If you just want a `.zip` containing an individual project, go to the project's GitHub link on the [Projects](Projects.md) page. On the right, there is a **Download ZIP** button.

##Downloading Everything
Note that this may take considerable time and space. In your terminal, go to the directory in which you want the Catalyst folder to be contained. Type:
```
git clone path/to/repo --recursive-submodules
```
This will get you the most recent Catalyst releases of every project **and** all of their submodules, recursively.

##Updating Everything
This may take considerable time depending on how long it has been since you last updated everything. In the Catalyst root directory, type:
```
git pull path/to/repo
git submodule update --init --recursive
```

##Getting Catalyst
For if you want to be able to download individual projects. In your terminal, go to the directory in which you want the Catalyst folder to be contained. Type:
```
git clone path/to/repo
```
This will download the Catalyst repository but none of the Projects. 

##Downloading Individual Projects
