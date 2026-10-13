# Linux_Notes

## Shell Commands Learnt On 11th Oct 2026

1. **ls -lSh** : This will list out sorted size of files from largest > Smallest

3. **--help** : This will help to know other existing flags in the command

4. **man** : This will further give detail of possible flags for the command
5. **grep '^sai'** : This will list all files and folders starting with 'sai' letters.

6. **grep 'end$'** : This will list all files and folders ending with 'end' letters.

7. **head /(directory_details)** : This will list out top 10 lines of the file content

8. **head -n (Count) /directory_details)** : This will only list the count lines from top of the file content.

9. **tail /(directory_details)** : This will list out bottom 10 lines of the file content

8. **tail -n (Count) /directory_details)** : This will only list the count lines from bottom of the file content.

## Shell Commands Learnt On 12th Oct 2026

1. **less** : This command will help us to open large text files in the PDF viewer style where it helps us to easily navigate through the entire content without confusion. And this feature provides shortcut key Like:
    **Space or f** - page down.
    **b** - page up.
    **g** - jump to the top.
    **G (capital)** - jump to the bottom.
    **/word** - search forward for word. Press n for the next match.
    **?word** - search backward.
    **q** - quit and return to the shell.

2. **tail -f /var/log/app.log** : This will display and tracks latest application logs.

3. **tail -F /var/log/app.log** : This will display and tracks latest application logs. Also in case of file recreation or renamed ( If in case the same old log file is created with new name)

4. **>>** : This command will append the new text to the previous text in the file.

5. **<** : This command will point a certain directory

6. **>** : This command will add output or text to a file. If the file already has a content then it will earase the existing content and add this new content.

7. **grep -i "String" /Directory path** : This command will pick the string irrespective of any case-sensitive text format. 
   Eg: **STring or string, STRING, sTiNg** etc...
