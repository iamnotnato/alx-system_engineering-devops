> 🚧 **Project :** 0x01-shell_permissions

<br>

> 📝 **Summary:**

>These are projects that helped me understand bash scripting.

<br>

> ⌨️ **Languages Used :**

<table>
  <tr>
    <td><img alt="medium" src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white"></td>
    <td><img alt="medium" src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white"></td>
  </tr>
</table>

<br>

> 🖥️ **Integrated Development Environment:**

<table>
  <tr>
<td><img alt="medium" src="https://img.shields.io/badge/Emacs-%237F5AB6.svg?&style=for-the-badge&logo=gnu-emacs&logoColor=white"></td>
  </tr>
</table>

<br> 

> ✒️ **List of Tasks:**

<br>

> 📁 **0. My name is Betty**
> 
> 💾 **File :** [0-iam_betty](./0-iam_betty)
> 
> 📑 **Task :** A script that switches the current user to the user betty.
>
> 📝 **Required :** 

<br>

| | Guides                                                                                   |
|-| ---------------------------------------------------------------------------------------- |
|-| You should use exactly 8 characters for your command (+1 character for the new line)     | 
|-| You can assume that the user betty will exist when we will run your script               |

<br> 

> 📝 **Notes :** 

> The Unix command su, which stands for 'substitute user' (or historically 'superuser'), is used by a computer user to execute commands with the privileges of another user account.
 
<br>

> 📁 **1. Who am I**
> 
> 💾 **File :** [1-who_am_i](./1-who_am_i)
> 
> 📑 **Task :** A script that prints the effective username of the current user.
> 
<br>  
 
> 📁 **2. Groups**
> 
> 💾 **File :** [2-groups](./2-groups)
> 
> 📑 **Task :** A script that prints all the groups the current user is part of.
> 
<br>   
   
> 📁 **3. New owner**
> 
> 💾 **File :**: [3-new_owner](./3-new_owner)
> 
> 📑 **Task :** A script that changes the owner of the file hello to the user betty.
> 
<br> 
 
> 📁 **4. Empty!**
> 
> 💾 **File :** [4-empty](./4-empty)
> 
> 📑 **Task :** A script that creates an empty file called hello.
> 
<br>   
   
> 📁 **5. Execute**
> 
> 💾 **File :** [5-execute](./5-execute)
> 
> 📑 **Task :** A script that adds execute permission to the owner of the file hello.
> 
<br> 
 
> 📁 **6. Multiple permissions**
> 
> 💾 **File :** [6-multiple_permissions](./6-multiple_permissions)
> 
> 📑 **Task :** A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
> 
> 📝 **Footnotes :** 

> Linux is a multi-user operating system, so it has security to prevent people from accessing each other’s confidential files.

<h5> Understanding the security permissions </h5>

> First, you must think of those nine characters as three sets of three characters (see the box at the bottom). Each of the three “rwx” characters refers to a different operation you can perform on the file. 
 

| rwx  |  rwx   | rwx   |
|----- |------- |------ |
| user |  group | other |
 

**Read, write, execute and –**

> The ‘r’ means you can “read” the file’s contents.
> 
> The ‘w’ means you can “write”, or modify, the file’s contents.
> 
> The ‘x’ means you can “execute” the file. This permission is given only if the file is a program.
> 
> If any of the “rwx” characters is replaced by a ‘-‘, then that permission has been revoked. 

 

<h5> User, group and others </h5>

> user – The user permissions apply only the owner of the file or directory, they will not impact the actions of other users.
>
> group – The group permissions apply only to the group that has been assigned to the file or directory, they will not effect the actions of other users.
>
> others – The others permissions apply to all other users on the system, this is the permission group that you want to watch the most. 

<h5> Reading the security permissions</h5>

> For example, consider that the user’s permissions for some files is “rw-” as the first three characters.
>
> This means that the owner of the file can “read” it (look at its contents) and “write” it (modify its contents).
>
> I cannot execute it because it is not a program; it is a text file. 

> If “r-x” is the second set of 3 characters it means that the members of the group can only read and execute the files. 

> The final three characters show the permissions allowed to anyone who has a UserID on this Linux system.
>
> Let us say we have the permission (“r–“). This means anyone in our Linux world can read, but they cannot modify the contents of the files or execute it. 

<h5> Changing security permissions</h5>

> The command you use to change the security permissions on files is called “chmod”, which stands for “change mode”, because the nine security characters are collectively called the security “mode” of the file. 

> The first argument you give to the “chmod” command is ‘u’, ‘g’, ‘o’. We use: 
>u for user 
>g for group 
>o for others, 
>you can also use a combination of them (u,g,o). 
>This specifies which of the three groups you want to modify. 
 
> After this use 
> a ‘+’ for adding 
> a ‘-‘ for removing 
> and a “=” for assigning a permission.
> Then specify the permission r,w or x you want to change. 
> Here also you can use a combination of r,w,x. 
> This specifies which of the three permissions “rwx” you want to modify
> use can use commas to modify more permissions
> Finally, the name of the file whose permission you are changing
> An example will make this clearer. 
> For example, if you want to give “execute” permission to the world (“other”) for file “xyz.txt”, you would start by typing 
 

> chmod o
> Now you would type a ‘+’ to say that you are “adding” a permission. 
 

> chmod o+
> Then you would type an ‘x’ to say that you are adding “execute” permission. 
 

> chmod o+x
> Finally, specify which file you are changing. 
 

> chmod o+x xyz.txt


> You can also change multiple permissions at once. For example, if you want to take all permissions away from everyone, you would type 
 

> chmod ugo-rwx xyz.txt
> The code above revokes all the read(r), write(w) and execute(x) permission from all user(u), group(g) and others(o) for the file xyz.txt which results to this. 
 

> multiple use

> Another example can be this: 
 

> chmod ug+rw,o-x abc.mp4
> The code above adds read(r) and write(w) permission to both user(u) and group(g) and revoke execute(x) permission from others(o) for the file abc.mp4. 

> Something like this: 
 

> chmod ug=rx,o+r abc.c
> assigns read(r) and execute(x) permission to both user(u) and group(g) and add read permission to others for the file abc.c. 

> There can be numerous combinations of file permissions you can invoke, revoke and assign. You can try some in your linux system. 

<h5> The octal notations</h5>

> You can also use octal notations like this. 


<h6> Octal Table <h6>
  
 <br>

<img src="https://github.com/iamnotnato/alx-system_engineering-devops/blob/master/0x01-shell_permissions/images/octal-notation.jpg" width="600">

> Using the octal notations table instead of ‘r’, ‘w’ and ‘x’. Each digit octal notation can be used of either of the group ‘u’,’g’,’o’. 

> So, the following work the same. 
 

> chmod ugo+rwx [file_name]
> chmod 777 [file_name]
> Both of them provides full read write and execute permission (code=7) to all the group. 

> Same is the case with this.. 
 

> chmod u=r,g=wx,o=rx [file_name]
> chmod 435 [file_name]
> Both the codes give read (code=4) permission to user, write and execute (code=3) for group and read and execute (code=5) for others. 

> And even this… 
 

> chmod 775 [file_name]
> chmod ug+rwx,o=rx [file_name]
> Both the commands give all permissions (code=7) to user and group, read and execute (code=5) for others. 

<br>   
   
> 📁 **7. Everybody!**
> 
> 💾 **File :** [7-everybody](./7-everybody)
> 
> 📑 **Task :** A script that adds execution permission to the owner, the group owner and the other users, to the file hello
>
> 📝 **Required :** 

<br>

| | Guides                                              |
|-| --------------------------------------------------- |
|-| You are not allowed to use commas for this script.  |
 
<br> 
 
> 📁 **8. James Bond**
> 
> 💾 **File :** [8-James_Bond](./8-James_Bond)
> 
> 📑 **Task :** A script that sets the permissions stated.
> 
> 💡*Fun Fact : James Bond is a fictional character created by British novelist Ian Fleming in 1953.* 
> 
> *A British secret agent working for MI6 under the codename 007, Bond has been portrayed on film in twenty-seven productions by actors*
>
> 📝 **Required :** 

<br>

| | Guides                                |
|-| ------------------------------------- |
|-| Owner: no permission at all           | 
|-| Group: no permission at all           |
|-| Other users: all the permissions      |

<br> 

> 📁 **9. John Doe**
> 
> 💾 **File :** [9-John_Doe](./9-John_Doe)
> 
> 📑 **Task :** A script that sets the mode of the file to -rwxr-x-wx.
>
> 💡*Fun Fact : John Doe and Jane Doe are multiple-use placeholder names that are used when the true name of a person is unknown or is being intentionally concealed.*
>  
> *In the context of law enforcement in the United States, such names are often used to refer to a corpse whose identity is unknown or unconfirmed.*
> 
> 📝 **Required :** 

<br>

| | Guides                                              |
|-| --------------------------------------------------- |
|-| You are not allowed to use commas for this script.  |
 
<br> 
 
> 📁 **10. Look in the mirror**
> 
> 💾 **File :** [10-mirror_permissions](./10-mirror_permissions)
> 
> 📑 **Task :** A script that sets the mode of the file hello the same as olleh’s mode.
> 
> ✍️ *Idiom : To consider, realize, or admit one's own failing or culpability in relation to some issue.*
>
> 📝 **Required :** 

<br>

| | Guides                                                                              |
|-| ----------------------------------------------------------------------------------- |
|-| the mode of olleh will not always be 664. Make sure your script works for any mode. |
 
<br> 
 
> 📁 **11. Directories**
> 
> 💾 **File :**: [11-directories_permissions](./11-directories_permissions)
> 
> 📑 **Task :** A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
>
> 📝 **Required :** 

<br>

| | Guides                               |
|-| ------------------------------------ |
|-| Regular files should not be changed. |

<br> 
 
> 📁 **12. More directories**
> 
> 💾 **File :** [12-directory_permissions](./12-directory_permissions)
> 
> 📑 **Task :** A script that creates a directory called my_dir with permissions 751 in the working directory.
> 
<br>  
  
> 📁 **13. Change group**
> 
> 💾 **File :** [13-change_group](./13-change_group)
> 
> 📑 **Task :** A script that changes the group owner to school for the file hello
> 
<br> 
 
> 📁 **14. Owner and group**
> 
> 💾 **File :** [100-change_owner_and_group](./100-change_owner_and_group)
> 
> 📑 **Task :** A script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
> 
<br>   
   
> 📁 **15. Symbolic links**
> 💾 **File :** [101-symbolic_link_permissions](./101-symbolic_link_permissions)
> 
> 📑 **Task :** A script that changes the owner and the group owner of _hello to vincent and staff respectively.
> 
<br> 
 
> 📁 **16. If only**
> 
> 💾 **File :** [102-if_only](./102-if_only)
> 
> 📑 **Task :** A script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
> 
<br>  
  
> 📁 **17. Star Wars**
> 
> 💾 **File :** [103-Star_Wars](./103-Star_Wars)
> 
> 📑 **Task :** A script that will play the StarWars IV episode in the terminal.
> 
> 💡*Fun Fact : "Star Wars is an American epic space opera multimedia franchise created by George Lucas, which began with the eponymous 1977 film and quickly became a worldwide pop-culture phenomenon.*
> 
