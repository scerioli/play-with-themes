# play-with-themes

## Creating GitHub Pages from scratch

- Start creating a new repo on GitHub

- Clone it locally

- Create a folder called docs ```mkdir docs``` and enter it ```cd docs```

- Run ```jekyll new .```

- Open the Gemfile that Jekyll created.

- Add "#" to the beginning of the line that starts with gem "jekyll" to comment out this line.

- Add the github-pages gem by editing the line starting with # gem "github-pages". Change this line to:
```gem "github-pages", "~> GITHUB-PAGES-VERSION", group: :jekyll_plugins```
Replace GITHUB-PAGES-VERSION with the latest supported version of the github-pages gem. You can find this version here: "[Dependency versions](https://pages.github.com/versions/)."

- Save and close the Gemfile.

- From the command line, run bundle update.

- Modify the _config.yml according to what you wish to have