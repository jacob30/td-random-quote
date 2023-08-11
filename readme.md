# Getting Started:

1. Clone the project from github eg.

- Latest commit `git clone https://github.com/XXXX/XXXX.git`
- Specific commit `git@gist.github.com:XXXX.git`

2. Move into the directory eg. `cd td-1`
3. Open the index.html file eg. `open -a "Safari" index.html`

Expected output:

![Image 5](https://github.com/jacob30/gh-assets/blob/main/td1a.gif)

System Requirements:

- Zsh 5.9 (arm-apple-darwin21.3.0)
- Mac OS X Ventura 13.4

Browser compatibility:

- Safari Version 16.5 ✅
- Chrome ❌

Notes:

- if you get `src refspec master does not match any` then you need to commit some code to the branch. `git add .` >> `git commit -m "done: X"` >> `git push`
- I have multiple git accounts so I use local git config, add this to your .git/config file to set the user:

```
[user]
    name = UserName
    email = user@domain.com
```

- gitconfig is not cached anywhere, you don't need to reload it. Just edit it and it'll be used on the next git command. You cannot source it because source is for shell config files and . gitconfig is a git config.
- gitattributes is for defining attributes per path (not used here).
- useful commands: `git branch -r` view branches, `git remote -v` view remotes.
