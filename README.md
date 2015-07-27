# Operation Code Blog

Built with the [Casper](https://github.com/TryGhost/Casper) theme on top of [Middleman-Blog](http://middlemanapp.com/basics/blogging/).


## Installation

1. Fork this repo and then clone your repo to the desktop. `git clone <repo url>`


## Usage

Enter in the following commands
```bash
bundle install
git checkout source
cd source/articles
```

Copy one of the existing markdown files and update the title, author, and date fields. Update the filename itself to correspond to the changes. Overwrite the blog post content with your own.

Once finished, while still in the source branch, enter the following:
```bash
git add .
git commit
git push
```

Once the changes are pushed to your repo, open a pull request to submit changes to Operation Code blog repo.


## Blog Owner

After merging the commits, pull down the new commits and run the following to update the website.

```bash
middleman build
middleman deploy
```
