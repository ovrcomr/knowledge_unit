## Working directory

<br>

The working directory can be compared as the first layer of the **Git** workflow.  
This is where the user interact with files, and makes modifications.

```bash
$ ls

    file1.txt
    file2.txt
    file3.txt

```

**Git** is aware that those files exists and contains what they does.
But the version control system do not interfer yet with the files.

```bash

$ git status

Untracked files:
    (use "git add <file>..." to include in what will be commtied)
    file1.txt
    file2.txt
    file3.txt
```

