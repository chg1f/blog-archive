---
title: "Git Conventions" # Title of the blog post.
date: 2020-12-15T14:57:21+08:00 # Date of post creation.
# description: "Article description." # Description used for search engine.
# featured: true # Sets if post is a featured post, making appear on the home page side bar.
# menu: main
# featureImage: "/images/path/file.jpg" # Sets featured image on blog post.
# thumbnail: "/images/path/thumbnail.png" # Sets thumbnail image appearing inside card on homepage.
# shareImage: "/images/path/share.png" # Designate a separate image for social media sharing.
# codeMaxLines: 10 # Override global value for how many lines within a code block before auto-collapsing.
# codeLineNumbers: false # Override global value for showing of line numbers within code block.
# figurePositionShow: true # Override global value for showing the figure label.
# comment: false # Disable comment if false.
toc: true # Controls if a table of contents should be generated for first-level links automatically.
categories:
  - note
tags:
  - git
  - convention
---

**Insert Lead paragraph here.**

## Commit Message

### Conventional Commits

#### Commit First Line Prefix

1. build: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
1. chore: Other changes that don't modify src or test files
1. ci: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
1. docs: Documentation only changes
1. feat: A new feature
1. fix: A bug fix
1. perf: A code change that improves performance
1. refactor: A code change that neither fixes a bug nor adds a feature
1. revert: Reverts a previous commit
1. style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
1. test: Adding missing tests or correcting existing tests

> References
> - https://www.conventionalcommits.org/en/v1.0.0/
> - https://github.com/angular/angular/blob/master/CONTRIBUTING.md
> - https://github.com/commitizen/conventional-commit-types/blob/master/index.json

## Branch Naming

### GitFlow

#### Branch Prefix

1. feature/features
1. bugfix/hotfix
1. develop
1. release
1. master

> References
> - https://github.com/nvie/gitflow
> - https://nvie.com/posts/a-successful-git-branching-model/
> - https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

## Git Docs

https://git-scm.com/book/en/v3
