# **Command-Line Cheat Sheet**
This cheat sheet provides a summary of command-line commands that can be used in the terminal, including Git commands.

<br>

## Terminal

### Navigation Commands

| Command | Description |
| ------- | --------------------- |
| `pwd` | Short for "**p**rint **w**orking **d**irectory". <br> Can be used to determine which directory you are currently in, including the path followed to get there. |
| `ls` | Lists all files and folders within the current directory (excluding hidden files/folders). Can be combined with *flags*, as described below. |
| `ls -l` | On top of `ls`, the `-l` flag can be used to show additional information about all shown files/folders, inlcuding owner, permissions and date last modified. |
| `ls -a` | On top of `ls`, the `-a` flag can be used to show hidden files/folders. |
| `ls -al` | Combines the `-a` and -`l` flags, showing all files/folders including those hidden, with additional information. |
|  `cd` | Short for "**c**hange **d**irectory". Used to move between directories. <br> **Use cases:**<ul><li>```cd``` on its own takes you to your home directory;</li><li>`cd -` takes you to the directory you were in directly prior;</li><li>`cd Documents` takes you into the Documents folder. It can be used whilst in the parent folder of Documents.</li><li>`cd Documents/coursework` takes you into the coursework folder, that is within the Documents folder. It can be used whilst in the parent folder of Documents.</li><li>`cd ..` is used to move into the parent directory of the current one.</li><li>Whilst using `cd`, it can be useful to keep in mind that the `tab` key can be used to autocomplete commands. If there are multiple autocomplete options, `tab` can be used repeatedly to select which option to use, before hitting `return` to confirm the selection.</li></ul> |

<br>

### Creating Files and Folders

Follow these rules for naming new files/folders:

1. Do not use / or . in file names.
    - Also, avoid using \ as it is a separator character in Windows
1. Avoid using spaces/whitespace: use underscores (_) instead, or capitalise letters - follow one of the following conventions to keep professionality:
    - `snake_case` - this is where spaces are replaced by underscores, and is the most popular file naming convention.
    - `camelCase` - this is where spaces are eliminated by capitalising the following letter.

## Git