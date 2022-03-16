# FactoryTalk Vault Quick Start

This repository contains a two sample solutions.
Blah blah...

## Repository Organization

You are free to organize your repository in any manner you choose with one
exception: the `.vault` folder must exist at the root of the repository.

This example repo uses folders to group related content:

```text
.
├─ .vault           # Contains FTVault specific content.
│  └─ vault.yaml    # Describes the structure of this repository to FTVault.
|                   #   See the 'Resource' section for more information.
|
├─ Line ABC         # Contains an example solution
│  ├─ src
│  │  ├─ proja.acd  # A sample LogixDesigner project
│  │  └─ machines   # Contains a sample FTDS project
│  ├─ tests         # Contains tests and simulations
│  |  └─ sim.e3d    # A sample Emulate3D project
│  ├─ lineabc.pdf   # Misc solution files
│  └─ lineabc.drw
|
├─ Line XYZ         # Contains a second solution
│     └─ ...
|
├─ shared           # Contains content shared among the solutions
│  └─ src
│     └─ shared.acd
|
└─ README.md        # This file
```

## Resources

### FactoryTalk Vault
- [Vault.yaml](#) reference
- [FactoryTalk Vault](#) home page
- [FactoryTalk Hub](#) home page
- etc.

### Learning git
- [An Intro to Git and GitHub for Beginners (Tutorial)](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)
- [Pro Git book](https://git-scm.com/book)
- [Git reference](https://git-scm.com/docs)
- etc.

### Graphical interfaces for git
- [GitHub Desktop](https://desktop.github.com/)
- [SourceTree](https://www.sourcetreeapp.com/)
- etc.
