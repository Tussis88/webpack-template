### Deploy on GitHub Pages
- To deploy the project you need to create a new branch with `git branch gh-pages`.
- Then run `git checkout gh-pages` to change branch and `git merge main --no-edit` and sync your changes from main.
- build your `dist/` folder with the command `npm build`.

- Now you neeed to remove `dist/` from your `.gitignore` file, than `add` and `commit` the changes.
- Now run the command `npm deploy` and then you can go back to main with `git checkout main`.

> You need to create the new branch just the first time.