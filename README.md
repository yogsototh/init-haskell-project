# Holy Haskell

This very simple script will initialize your new Haskell project.
It will initialize the `.gitignore` file, the cabal file and give an
example of test suite.

# Usage

Clone the repository locally and launch the script:

```
./holy-haskell.sh
```

It will ask some questions, do your best dear aventurer!

## dependencies

- [Haskell](http://haskell.org/platform)
- [`cabal`](http://haskell.org/cabal) version at least 1.18 ; to install it:

    ```
    cabal update
    cabal install cabal-install
    ```
- [`git`](http://git-scm.org)
- [`zsh`](http://zsh.org) which should be already installed on most platform
