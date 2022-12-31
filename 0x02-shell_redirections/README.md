<h4>Project : 0x02-shell_redirections</h4>
<h4>Summary: </h4>
These are projects that helped me understand bash scripting.

<h4>Languages Used</h4>
<table>
  <tr>
    <td><img alt="medium" src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white"></td>
    <td><img alt="medium" src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white"></td>
  </tr>
</table>

<h4>Integrated Development Environment:</h4>
<table>
  <tr>
<td><img alt="medium" src="https://img.shields.io/badge/Emacs-%237F5AB6.svg?&style=for-the-badge&logo=gnu-emacs&logoColor=white"></td>
  </tr>
</table>
  
  <h4>List of Tasks:</h4>

* **0. Hello World**
  * File : [0-hello_world](./0-hello_world)
  * Required : A script that prints “Hello, World”, followed by a new line to the standard output.
<br> 
 
* **1. Confused smiley**
  * File : [1-confused_smiley](./1-confused_smiley)
  * Required : A script that displays a confused smiley "(Ôo)'.
<br>  
 
* **2. Let's display a file**
  * File : [2-hellofile](./2-hellofile)
  * Required : Display the content of the /etc/passwd file.
<br>   
   
* **3. What about 2?**
  * File : [3-twofiles](./3-twofiles)
  * Required : Display the content of /etc/passwd and /etc/hosts.
<br> 
 
* **4. Last lines of a file**
  * File : [4-lastlines](./4-lastlines)
  * Required : Display the last 10 lines of /etc/passwd
<br>   
   
* **5. I'd prefer the first ones actually**
  * File : [5-firstlines](./5-firstlines)
  * Required : Display the first 10 lines of /etc/passwd
<br> 
 
* **6. Line #2**
  * File : [6-third_line](./6-third_line)
  * Required : A script that displays the third line of the file iacta.
  * Expected Results :
    * You’re not allowed to use sed.
<br>   
   
* **7. It is a good file that cuts iron without making a noise**
  * File : [7-file](./7-file)
  * Required : A shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
<br> 
 
* **8. Save current state of directory**
  * File : [8-cwd_state](./8-cwd_state)
  * Required : 
    * A script that writes into the file ls_cwd_content the result of the command ls -la. 
    * If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
<br>    
    
* **9. Duplicate last line**
  * File : [9-duplicate_last_line](./9-duplicate_last_line)
  * Required : A script that duplicates the last line of the file iacta
<br> 
 
* **10. No more javascript**
  * File : [10-no_more_js](./10-no_more_js)
  * Required : A script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
<br> 
 
* **11. Don't just count your directories, make your directories count**
  * File : [11-directories](./11-directories)
  * Required : A script that counts the number of directories and sub-directories in the current directory.
  * Expected Results :
    * The current and parent directories should not be taken into account.
    * Hidden directories should be counted.
<br> 
 
* **12. What’s new**
  * File : [12-newest_files](./12-newest_files)
  * Required : A script that displays the 10 newest files in the current directory.
  * Expected Results :
    * One file per line.
    * Sorted from the newest to the oldest.
<br>  
  
* **13. Being unique is better than being perfect**
  * File : [13-unique](./13-unique)
  * Required : A script that takes a list of words as input and prints only words that appear exactly once.
  * Expected Results :
    * Input format: One line, one word.
    * Output format: One line, one word.
    * Words should be sorted.
<br> 
 
* **14. It must be in that file**
  * File : [14-findthatword](./14-findthatword)
  * Required : Display lines containing the pattern “root” from the file /etc/passwd
<br>   
   
* **15. Count that word**
  * File : [15-countthatword](./15-countthatword)
  * Required : Display the number of lines that contain the pattern “bin” in the file /etc/passwd
<br> 
 
* **16. What's next?**
  * File : [16-whatsnext](./16-whatsnext)
  * Required : Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
<br>  
  
* **17. I hate bins**
  * File : [17-hidethisword](./17-hidethisword)
  * Required : Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
<br> 
 
* **18. Letters only please**
  * File : [18-letteronly](./18-letteronly)
  * Required : Display all lines of the file /etc/ssh/sshd_config starting with a letter.
  * Expected Results :
    * include capital letters as well.
<br>  
  
* **19. A to Z**
  * File : [19-AZ](./19-AZ)
  * Required : Replace all characters A and c from input to Z and e respectively.
<br>

* **20. Without C, you would live in hiago**
  * File : [20-hiago](./20-hiago)
  * Required : A script that removes all letters c and C from input.
<br>  
  
* **21. esreveR**
  * File : [21-reverse](./21-reverse)
  * Required : A script that reverse its input.
  
💡*Fun Fact : Esrever is simply the word REVERSE in reverse.*
<br>

* **22. DJ Cut Killer**
  * File : [22-users_and_homes](./22-users_and_homes)
  * Required : A script that displays all users and their home directories, sorted by users.

💡*Fun Fact : DJ Cut Killer or simply Cut Killer, is a Moroccan-born French DJ and record producer with a versatile repertoire of hip hop music.*
<br>  
  
* **23. Empty casks make the most noise**
  * File : [100-empty_casks](./100-empty_casks)
  * Required : A command that finds all empty files and directories in the current directory and all sub-directories.
  * Expected Results :
    * Only the names of the files and directories should be displayed (not the entire path)
    * Hidden files should be listed.
    * One file name per line.
    * The listing should end with a new line.
    * You are not allowed to use basename, grep, egrep, fgrep or rgrep.

💡*Fun Fact :  “Empty barrels make the most noise” is a phrase which refers to how people with little to say are often the loudest.*
<br>

* **24. A gif is worth ten thousand words**
  * File : [101-gifs](./101-gifs)
  * Required : A script that lists all the files with a .gif extension in the current directory and all its sub-directories.
  * Expected Results :
    * Hidden files should be listed.
    * Only regular files (not directories) should be listed.
    * The names of the files should be displayed without their extensions.
    * The files should be sorted by byte values, but case-insensitive
      *(file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
    * One file name per line.
    * The listing should end with a new line.
    * You are not allowed to use basename, grep, egrep, fgrep or rgrep.

💡*Fun Fact :  “It is based on a fantastic post by Jennifer Taylor on the origin of the GIF*
<br>  
  
* **25. Acrostic**
  * File : [102-acrostic](./102-acrostic)
  * Required : A script that decodes acrostics that use the first letter of each line.
  * Expected Results :
    * The ‘decoded’ message has to end with a new line.
    * You are not allowed to use grep, egrep, fgrep or rgrep.

💡*Fun Fact :  “An acrostic is a poem or other word composition in which the first letter of each new line spells out a word, message or the alphabet.*
<br>

* **26. The biggest fan**
  * File : [103-the_biggest_fan](./103-the_biggest_fan)
  * Required : A script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
  * Expected Results :
    * Order by number of requests, most active host or IP at the top.
    * You are not allowed to use grep, egrep, fgrep or rgrep.
<br>
