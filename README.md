# Introduction
Given a `root` directory, for each file in each subdirectory, this ipython notebook (1) prepends the subdirectory name to the file name, (2) moves the file into `root`, and (3) deletes the subdirectory, if it is empty.

# Example
Consider this file system:
```
main-directory
    alpha
        item-1.jpg
        item-2.jpg
    bravo
        item-1.jpg
        item-2.jpg
```
If we set `root` to `main-directory` and run the notebook, the system will be changed to
```
main-directory
    alpha_item-1.jpg
    alpha_item-2.jpg
    bravo_item-1.jpg
    bravo_item-2.jpg
```
