# Bootstrap Project 1

The challenge is to take the custom css and replace it with bootstrap classes. There may be elements that cannot be replaced just to make you think. I will do a code review with each of you after you push up your `develop-<your-name-here>` branch to my repository: https://github.com/kelsu02/bootstrap-project-1.

Bootstrap: https://getbootstrap.com/

## GIT Flow

### Initial Setup

1. In your GitHub account create a new project bootstrap-project-1
2. In your terminal cd into your projects (or what your name is) folder
3. Clone down the repository: `git clone https://github.com/kelsu02/bootstrap-project-1`
    - If you are on a Mac you might need to clone down with the SSH key instead of the Https
    - This sets up the origin remote
        - To push to this remote: `git push origin`
4. cd into bootstrap-project-1
5. Checkout a develop branch with your name: `git checkout -b develop-<your-name-here>`
    - This command creates a new branch and puts you on it. It's the equivalent of `git
6. Set up your upstream remote (to your repository): `git remote add upstream https://github.com/<your-user-name>/bootstrap-project-1`
    - Same thing here about the SSH key instead of the Https
    - To push to this remote: `git push upstream`  

More information on git remotes: https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes

### Updating the CSS

1. Open up the project in VSCode
    - if you are coming from your terminal type `code .` while you are in that project and it should open up.
2. In the index.html add the cdn for bootstrap above the call for the CSS stylesheet.
    - `<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-F3w7mX95PdgyTmZZMECAngseQB83DfGTowi0iMjiWaeVhAn4FJkqJByhZMI3AhiU" crossorigin="anonymous">`
3. Update the css classes so you use as much bootstrap and as little custom css as possible.

### Submitting your solution

1. After you have a solution commit your changes
    - `git status`
        - You can git status at any time to see what files are staged for your commit and to see which ones have been changed but aren't included in this commit
    - `git add .` or `git add <filename>` 
        - 2nd option if you have made changes in unrelated files and you don't want to include them in this commit
    - `git commit -m "Message about your solution"`
        - The message should be descriptive to tell others what you accomplished.
2. Push your changes to the Origin repository
    - FIRST PUSH: `git push --set-upstream origin develop-<your-name>`
    - `git push origin`
        - You should see this remote information: To https://github.com/kelsu02/bootstrap-project-1 
        - To check remote `git remote -v`
3. Push your changes to your own repository (if you want to keep a copy)
    - FIRST PUSH: `git push --set-upstream upstream develop-<your-name>`
    - `git push upstream`
        - You should see this remote information: To https://github.com/<your-github-username\>/bootstrap-project-1.git
        - to check remote `git remote -v`

If you push to your own repository you can practice doing pull requests to your main branch and see the process from start to finish. Doing pull requests to your repository from your develop to your main will give you github activity.

Reach out to Kelly on Discord if you need help with any of the steps above
