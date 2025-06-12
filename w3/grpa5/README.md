Question:
```
Print the number of directories in the current working directory. Do not print anything else.

Hint: One solution is to make use of 'ls', 'wc' and pipes('|').
```
Solution:
```bash
ls -l | grep ^d | wc -l
```
