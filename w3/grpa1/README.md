Question:
```
Print the number of lines present in 'file1' and 'file2' combined, your solution should
not print anything else. 'file1' and 'file2' are located in the current working directory.

Hint: Multiple files can be given as argument of 'cat' command.
```
Solution:
```bash
cat file1 file2 | wc -w
```
