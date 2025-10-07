# Playground

## Working with Git 
**Git is Flexible**
The Basic idea:
Your repository is on your computer and you can bring it into sync with other repositories (maybe somewhere else).

You are able to work without internet access
- Work on your own and sync later
- Work in a small team and sync only locally, e.g., LAN or memory stick
- Sync to repositories, e.g., send to you be snail mail

You are able to work with internet access
- Sync to other repositories over the internet
- Continuously sync to one central repository over the internet

**Working with a Git repository is – in principle – very simple**

  1. You make additions and changes in your workspace
  2. You add the changes you want to put in your repository to the index
  3. You commit these changes to the repository, specifying the topic of the changes
  4. You may refer to this later, push it somewhere else, or can continue with 1.

**Branches**

* When you work with a git repository you always work in a _branch_

  * The default _branch_ is called 'main'

* When you want to bring on a development undisturbed, want to test something without making your collaborators problems, you can make a new _branch_ for this
* Common are _branches_ for

  * A _branch_ for a working version (often the 'main' _branch_)
  * A _branch_ for development (often called 'development')
  * A _branch_ for new features (normally named after the feature that is realised)

* _Branches_ are like tags and have a name and refer to a commit, but a _branch_ name always refers to the latest _commit_
* You can _merge_ _branches_ by including all commits the branch to merge in the current branch (and deal with the conflicts)

In GitHub, you can create projects that allow you to host your codebase.

In addition of the *Git repository* a project includes

- issue tracker: powerful issue tracking system.
- merge requests: you can review and discuss code before it is merged
- and more

