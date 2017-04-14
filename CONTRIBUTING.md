# Contributing to RustBuilding.com

You might wonder why this isn't just a wiki where you can simply click edit on a page. The answer is curation and quality control; there are a number of Rust wikis, but this is meant to be something different. I'd rather *not* add content to this site than add poor-quality content.

That said, all contributions are much appreciated, no matter how big or small. I'm happy to just take suggestions on what to add, but there are ways to make bigger contributions too, if you're so inclined.

## How to contribute

Easier ways to contribute:
- Spread the word about RustBuilding.com
- Suggest something you'd like to see added
- Fix a typo
- Add a link to some existing video, guide, or other resource

More involved ways to make bigger contributions:
- Add a tip/trick/explanation/section to an existing page
- Make a new base layout overview page
- Write a guide on some aspect of building

If you have a suggestion for a page/explanation/detail/link/etc to add, [open an issue](https://github.com/LewisJEllis/rustbuilding.com/issues/new) and follow the issue template.

If you're fixing a typo or adding a link, feel free to just use the GitHub web interface and send a pull request. Check [this guide](https://help.github.com/articles/editing-files-in-another-user-s-repository/) for details on how to do that.

If you want to make a bigger addition/edit, you should get a copy of the site running locally so you can see how your changes look.

## Setting up a local copy of the site
You'll need to install [mkdocs](http://www.mkdocs.org/), fork + clone this repo, and run the site. If you're on a Mac with [homebrew](https://brew.sh), just do:
```
brew install mkdocs
git clone git@github.com:<YourGitHubUsername>/rustbuilding.com.git
cd rustbuilding.com
mkdocs serve
```
Then open http://localhost:8000, and you should have a local copy of the site that reflects any edits you make.

If you have no idea how git works but you want to learn, [start reading here](https://help.github.com/articles/git-and-github-learning-resources/).

## A word on bigger changes
If you're considering a bigger change/addition, it might be worth opening an issue to propose it and get a quick thumbs up first. I tend to have strict curation standards, and I don't want you to invest a bunch of time working on something that I won't add to the site.

For example, I would not accept a new base overview page for a base footprint that is an almost strictly worse variant of another footprint already featured on the site. It just wouldn't add anything; every base on the site should have some situation where it is among the best options for what to build.

Let the rest of the content on the site serve as an example of the quality bar to meet.
