
### Render the book (RStudio)

- [ ] 1. Install **bookdown** with `install.packages("bookdown")`. If you already have it, update to the most recent version.

- [ ] 2. Render locally with `bookdown::render_book("index.Rmd")` or clicking the *Build book* button which should appear in the Build tab (in the same pane as Environment, History, Connections, ...).

- [ ] 3. Use `browseURL("docs/index.html")` to view your book locally (or just open `index.html` in a browser).

- [ ] 4. If it looks good, commit and push all changed files to GitHub. 

(You will need to repeat steps 2 and 4 every time you wish to update the book online.)


If RStudio can't push/commit changes you may need to run the following in the RStudio terminal:
git config --global user.email "you@example.com"
git config --global user.name "Your Name"

(Needs to match git hub profile)