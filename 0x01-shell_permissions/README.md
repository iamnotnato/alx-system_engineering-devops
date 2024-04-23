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
