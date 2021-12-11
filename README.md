## Homework_2: XML Format
1. Create an external repository called TXT:
```
In GitHub account  click on the Your repositories -> New -> write Repository name -> Create repository
```
2. Clone the TXT repository to the local computer:
```
Click on the Code button and copy HTTPS -> In the Terminal type git clone and add HTTPS
```
3. Inside the local TXT, create a "new.txt" file: `touch new.txt`
4. Add the file under the git: `git add new.txt`
5. Commit the file: `git commit -m "Message`
6. Send the file to an external GitHub repository: `git push`
7. Edit the content of the file "new.txt" write information about yourself (name, age, number of pets, future desired salary). Write everything in XML format: `vim new.xml`
8. Send the changes to an external repository:
```
git commit -am "Message"
git push
```
9. Create "preferences.txt" file: `touch preferences.txt`
10. In the "preferences.txt" file, add information about your preferences (favorite movie, favorite show, favorite food, favorite time of year, party you would like to visit) in TXT format: `vim preferences.txt`
11. Create a "sklls.txt" file to add information about skills that will be studied on the course in TXT format:
```
touch skills.txt
vim skills.txt
```
12. Make one line commit: `git commit -am "Message"`
13. Send two files to external repository at once: `git push`
14. On the web interface, create a "bug_report.txt" file
15. Make Commit changes on the web interface:
```
In GitHub account click Add file -> Create new file -> add Commit new file -> Commit new file
```
17. On web interface modify "bug_report.txt" file, add bug report in TXT format
18. Make Commit changes (save) the changes in the web interface:
```
Сlick on pencil icon -> modify file -> add Commit new file -> Commit new file
```
20. Synchronize external and local TXT repository: `git pull`
