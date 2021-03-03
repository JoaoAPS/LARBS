# Luke's Auto-Rice Bootstraping Scripts (LARBS)

This is a fork of Luke Smith's Auto-Ricer.
The functionality is the same, only the configuration is different.

## Installation:

On an Arch based distribution as root, run the following:

```
wget https://raw.githubusercontent.com/JoaoAPS/LARBS/master/larbs.sh
sh larbs.sh
```

That's it.

### The `progs.csv` list

LARBS will parse the given programs list and install all given programs. Note
that the programs file must be a three column `.csv`.

The first column is a "tag" that determines how the program is installed, ""
(blank) for the main repository, `A` for via the AUR or `G` if the program is a
git repository that is meant to be `make && sudo make install`ed. `P` is for python
pip installs. `V`if it's for the void linux distribution's xbps package manager.

The second column is the name of the program in the repository, or the link to
the git repository, and the third comment is a description (should be a verb
phrase) that describes the program.

## Before formating
+ [ ] Backup home directories
+ [ ] Check that all repos are synched and pushed
+ [ ] Check that all configs are commited
+ [ ] Make sure that gnucash files and other documents are safe
+ [ ] Save private .ssh keys

## Additional Programs

This is a list of programs that LARBS won't install automatically, but that you may 
want to install afterwards.

### Programs LARBS can't install automatically
- [Reversal Icon Theme](https://github.com/yeyushengfan258/Reversal-icon-theme)

### Optional Programs
- VS Code
- Libre Office
- LaTeX
- Steam
- Tux Guitar
- Duplicity
- Julia
- sshfs
- cowsay
- Okular
- ipython

### Sublime Text Packages
- AdvancedNewFile
- Anaconda
- Babel
- EasyClangComplete
- Emmet
- Fileicons
- Fish
- GenericConfig
- Julia
- LaTeX-cwl
- LaTexTools
- LaTeXYZ
- MarkdownEditing
- MarkdownPreview
- Monokai - Spacegray
- MonokaiExtended
- Seti_UI
- SideBarEnhancements

### Julia Packages
- BenchmarkTools
- DataFrames
- Debugger
- DifferentialEquations
- LaTeXStrings
- OhMyRepl
- Plots
- PyPlot
- StatsBase
- StrLiterals
- StrFormat
- Query
