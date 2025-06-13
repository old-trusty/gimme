# Gimme
> **`Gi` t &nbsp;&nbsp;&nbsp;`M` eta &nbsp;&nbsp;&nbsp;ga `Me`**

A simple git clone wrapper + multitool that clones to a directory in a set repository directory by default 

```help
Usage:
    gm [options] <repo> <group> <alias>
        or
    gm <repo>

Arguments:
    <repo>
        the git repository url.
    <group>
        the directory to put the <repo> directory in.
    <alias>
        what to  call give <repo> directory.

Options:
    -h, --help
        print this help message.

!!! Options Not Implemented !!!:
    -s, spawn <repo>
        create and/or clone <repo> from a list of remotes (i.e. github, gitlab, sourcehut)
    -m, modify
        set remote repo options.
    -c, config 
        set gimme options.
    -g, graph
        asscii graph some kinds of git data.
    -a, alias
        create a top level alias in `gm [your-tool-here]` to any script
    -b, breathe
        very simple git porcelain
    
```
