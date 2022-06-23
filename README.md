# Git Conventions

## Table of contents
- [Repository](#repository)
- [Pull request](#pull-request)
- [Branch](#branch)
- [Commit](#commit)
- [Types](#type)
- [Scope](#scope)

## Repository

> You should use the [teki-lidi template](https://github.com/eteg/teki-lidi-template) when creating your repositories.
- Naming: kebab-cased (lowercase, words separated with hyphens)
- Readme with at least:
    - A short description of what the repository does
    - How to install
    - How to use
- License and Visibility: 
    - Private: No license should be used. [Why?](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository#choosing-the-right-license)
    - Public: Check with your Tech Lead first.


## Pull request

[type](#Type)([scope](#Scope)): ```Message```

> E.g. feat(context/sub-context): title of pull request

## Branch
[type](#Type)/kebab-cased-name
> E.g. feat/changing-wall-color

## Commit
[type](#Type)([scope](#Scope)): ```Message```
> E.g. feat: this is my cool commit
> 

## Type

`feat` add a new feature.

`fix` fix a bug.

`refactor` rewrite/restructure your code, however does not change any behaviour.

`test` add missing tests or correcting existing tests.

`docs` affect documentation only.

`chore` miscellaneous commits e.g. modifying .gitignore

`build` changes that affect build tools like, webpack, vite, NPM scripts...

`ci` affect pipeline files, like Github actions workflow.

> E.g. feat(home): cleaning up my house

## Scope
The scope provides contextual information.

- Is an optional part of the format
- Allowed Scopes depends on the specific project

> E.g. fix(home/living-room): add chair lag


## TODO

- [x] Create a repository template
- [ ] Badges implementation
- [ ] Contributing section
