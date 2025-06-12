Question:
```
"dir_1" and "dir_2" are directories in current working directory. Create a symbolic(soft) link to the file "file_1" present in "dir_1" and store it as "file_2" in "dir_2".
Hint: The link to file_2 should be either absolute from current working directory i.e. / or relative to dir_2.
```
Solution:
```bash
ln -s ${pwd}/dir_1/file_1 ${pwd}/dir_2/file_2
```
