# Contributing Guidelines

Thanks for thinking of contributing to this repository.

## Table of contents

- [Contributing Guidelines](#contributing-guidelines)
  - [Table of contents](#table-of-contents)
  - [Contributing guidelines](#contributing-guidelines-1)
    - [Become a contributor](#become-a-contributor)
    - [Workflow](#workflow)
  - [Repository structure](#repository-structure)
  - [Tools used](#tools-used)
    - [git](#git)
    - [Typora](#typora)
    - [VSCode](#vscode)
    - [Atom](#atom)

## Contributing guidelines

### Become a contributor

You can ask any of the existing project contributors for becoming a contributor. All you need is a GitHub ID and some knowledge in the [tools](#tools-used) used in this repository.

### Workflow

Follow this workflow to make changes and contribute to this repository. Make sure that you're a contributor before that.

1. Clone the repository on your local system before that
2. Create a branch with your first name followed by year of passing out. For example **Lorem Ipsum** in the Batch 2009 to 2013 would name the branch `lorem_2009`.
3. Make changes to the correct files.
4. Create a pull request to merge to the `dev` branch.
5. After other contributors review and finalize everything, the work shall be merged with the `master` branch and the pull request is then closed.

## Repository structure
Take a note of the main structure used.

Each immediate directory has a readme file which needs to be updated.

```
├── Advice
│   └──Batch_2016_2020
|
├── Course
│   ├── Batch_2016_2020
|   |
│   └── Topics
│       ├── Machine_Learning
│       ├── Mathematics
│       └── Robotics
|
├── Placements
│   ├── Batch_2020
│   └──docs
|
└── README.md

```
- Resources for the Mechatronics course are to be put in the [Course folder](./Course/README.md)

- Resources related to the placementsare to be put in the [Placement folder](./Placements/README.md)

- Valuable advice given by seniors are to be put in the [Advice folder](./Advice/README.md)

## Tools used

### git

Git is a tool used for version control. It's suggested that you get a little familiar with it. Atlassian has a great tutorial for [getting started](https://www.atlassian.com/git/tutorials).

Official page for git [here](https://git-scm.com/).

**You can use any of the following to edit and preview markdown files** :
- #### Typora

This is a great software to read and review files in this repository. You can get the software [here](https://typora.io/).

- #### VSCode

  - VSCode is an amazing text editor. You can get the editor [here](https://code.visualstudio.com/). The following extensions are suggested for the markdown files:
  - [Markdown All in One by Yu Zhang](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) for creating table of contents.
  - [markdownlint by David Anson](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

- #### Atom
In case you are using Atom you can view the markdown preview by pressing ```ctrl + shift + m```. Download atom [here](https://atom.io/)
