
# find-duplicates-fast-100
superfast duplicate finder in python, based on stack overflow post from Todor Minakov

https://stackoverflow.com/questions/748675/finding-duplicate-files-and-removing-them
<code> <pre> 
## 2024-08-30-1

-note: you must have python installed on your pc.
(If you don't have it installed, go to https://www.python.org/, 
move mouse over 'Downloads' and click on button under 'Download for Windows'
Save pythonxx.exe somewhere, and double click it to install it. Restart pc, or windows explorer.)

## installation:
-installation of program: right click on the link [here](https://github.com/dbojan/find-duplicates-fast-100/raw/main/find_duplicates_fast_100_python.zip), select "Save Link As"
-unzip somewhere

## usage:
-usage: drag and drop 'folder to search for duplicates' on 'find duplicates fast 100 - python - drop folder here.bat'

-wait for the result.

-'duplicates-move.bat' will be created. if you click on it, it will move duplicates to 'copies' folder.

-no warranty of any kind given.


-changes in 2020-08-30-1
 replaced delete with move, so file will be moved to folder 'copies', instead of deleted.

-changes in 2024-02-04-1:
 added 'chcp 65001>Nul' to the bat file to display utf8 encoded filenames in console
 changed encoding for files writen from python to 'utf-8'
 added space between file name and message 'filename still exists'
 changed name of a 'delete duplicates bat' file

-changes in 2023-08-21-1:
 small changes in readme.txt