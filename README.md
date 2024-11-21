# template

template repo for plain js/html/css dev (with node &amp; webpack)

Instructions to use this template in GitHub and for cloning:

- select this template when creating a new repo
- after cloning your new repo with the git clone command, you will not have the gh-pages branch, only the main
- to get the gh-pages branch cloned as well, list the remote branches from your local repo `git branch -r`
- then run `git checkout -b gh-pages origin/gh-pages`

Instructions for running the build (dev mode and prod mode):

- From the root path of the repo run `npm run dev` to start a web server and perform development
- the TOP webpack lesson has examples of how to import/export css/images/code <https://www.theodinproject.com/lessons/javascript-webpack>
- Use normal `git add .` and `git commit -m ...` to work on the files until the app is complete
- run `npm run build` when you're ready for production push (preview path will be http://localhost:8080/)
- then run `git checkout ghpages` followed by `git add dist -f` and `git commit -m "Deployment commit"`
- finally run `npm run deploy` to push the code out to the gh-pages branch, followed by `git checkout main` to return to the main branch
