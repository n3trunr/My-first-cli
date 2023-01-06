# My-first-cli
Python CLI following geeks4geeks tutorial

https://www.geeksforgeeks.org/command-line-interface-programming-python/

```
C:\My-first-cli>.\mycli.py -h
usage: mycli.py [-h] [num ...]

An addition program

positional arguments:
  num         All the numbers separated by spaces will be added.

optional arguments:
  -h, --help  show this help message and exit
```


```
C:\My-first-cli>.\tfmanager.py -h
usage: tfmanager.py [-h] [-r file_name] [-s path] [-d file_name] [-c file1 file2] [--rename old_name new_name]

A text file manager!

optional arguments:
  -h, --help            show this help message and exit
  -r file_name, --read file_name
                        Opens and reads the specified text file.
  -s path, --show path  Shows all the text files on specified directory path. Type '.' for current directory.
  -d file_name, --delete file_name
                        Deletes the specified text file.
  -c file1 file2, --copy file1 file2
                        Copy file1 contents to file2 Warning: file2 will get overwritten.
  --rename old_name new_name
                        Renames the specified file to a new name.
```
