> 🚧 **Project : 0x00-shell_basics**

<br>

> 📝 **Summary:**

>These are the projects that helped me understand bash scripting.

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

> 📁 **0. Where am I?**
>
> 💾 **File :** [0-current_working_directory](./0-current_working_directory)
>
> 📑 **Task :** A script that prints the absolute path name of the current working directory.
>
<br>

> 📁 **1. What’s in there?**
>
> 💾 **File :** [1-listit](./1-listit)
>
> 📑 **Task :** Display the contents list of your current directory.
>
<br>  
 
> 📁 **2. There is no place like home**
>
> 💾 **File :** [2-bring_me_home](./2-bring_me_home)
>
> 📑 **Task :** A script that changes the working directory to the user’s home directory.
>
> 🎵 **Lyric :** *"There's no place like home," the last line of the 1822 song "Home!*
>
> 📝 **Required :** 

<br>

| | Guides                                            |
|-| ------------------------------------------------- |
|-| You are not allowed to use any shell variables    | 

<br>
   
> 📁 **3. The long format**
>
> 💾 **File :** [3-listfiles](./3-listfiles)
>
> 📑 **Task :** Display current directory contents in a long format
>
<br> 
 
> 📁 **4. Hidden files**
>
> 💾 **File :** [4-listmorefiles](./4-listmorefiles)
>
> 📑 **Task :** Display current directory contents, including hidden files (starting with .). Use the long format.
>
<br>   
   
> 📁 **5. I love numbers**
>
> 💾 **File :** [5-listfilesdigitonly](./5-listfilesdigitonly)
>
> 📑 **Task :** Display current directory contents.
> 
> 📝 **Required :** 

<br>

| | Guides                                            |
|-| ------------------------------------------------- |
|-| Long format                                       | 
|-| with user and group IDs displayed numerically     |
|-| And hidden files (starting with .)                |

<br> 
 
> 📁 **6. Welcome**
>
> 💾 **File :** [6-firstdirectory](./6-firstdirectory)
>
> 📑 **Task :** A script that creates a directory named my_first_directory in the /tmp/ directory.
>
>📝 **Note :** `Mkdir -p`
>
>**-p.** Creates missing intermediate path name directories. 
>
>If the -p flag is not specified, the parent directory of each-newly created directory must already exist.
<br>   
   
> 📁 **7. Betty in my first directory**
>
> 💾 **File :** [7-movethatfile](./7-movethatfile)
>
> 📑 **Task :** Move the file betty from /tmp/ to /tmp/my_first_directory.
>
<br> 
 
> 📁 **8. Bye bye Betty**
> 
> 💾 **File :** [8-firstdelete](./8-firstdelete)
> 
> 📑 **Task :** Delete the file betty.
> 
<br>    
    
> 📁 **9. Bye bye My first directory**
> 
> 💾 **File :** [9-firstdirdeletion](./9-firstdirdeletion)
> 
> 📑 **Task :** Delete the directory my_first_directory that is in the /tmp directory.
> 
<br> 
 
> 📁 **10. Back to the future**
> 
> 💾 **File :**[10-back](./10-back)
> 
> 📑 **Task :** A script that changes the working directory to the previous one.
> 
> 💡*Fun Fact : "Back to the Future is a 1985 American science fiction film directed by Robert Zemeckis, and written by Zemeckis and Bob Gale."*
> 
<br> 

> 📁 **11. Lists**
> 
> 💾 **File :** [11-lists](./11-lists)
> 
> 📑 **Task :** A script that lists all files in the current directory.
>
> 📝 **Required :**

<br>

| | Guides                                                                              |
|-| ----------------------------------------------------------------------------------- |
|-| It lists all files in the the parent of the working directory.                      | 
|-| It lists all files in the /boot directory (in this order), in long format.          |
|-| (even ones with names beginning with a period character, which are normally hidden) | 

<br> 
 
> 📁 **12. File type**
> 
> 💾 **File :** [12-file_type](./12-file_type)
> 
> 📑 **Task :** A script that prints the type of the file named iamafile.
> 
<br>  
  
> 📁 **13. We are symbols, and inhabit symbols**
> 
> 💾 **File :** [13-symbolic_link](./13-symbolic_link)
> 
> 📑 **Task :** A symbolic link to /bin/ls, named __ls__.
>
> 💬 *Quote : "We are symbols, and inhabit symbols." - Ralph Waldo.*
>
> 📝 **Required :** 

<br>

| | Guides                                                                  |
|-| ----------------------------------------------------------------------- |
|-| The symbolic link should be created in the current working directory.   |

<br>

> 📝 **Footnotes :** 

> A symlink is a symbolic Linux/ UNIX link that points to another file or folder on your computer, or a connected file system. This is similar to a Windows shortcut.

> Symlinks can take two forms:

> Soft links are similar to shortcuts, and can point to another file or directory in any file system.

> Hard links are also shortcuts for files and folders, but a hard link cannot be created for a folder or file in a different file system.
 
<br> 
 
> 📁 **14. Copy HTML files**
> 
> 💾 **File :** [14-copy_html](./14-copy_html)
> 
> 📑 **Task :** A script that copies all the HTML files from the current working directory to the parent of the working directory.
>
> 📝 **Required :**

<br>

| | Guides                                                                                      |
|-| ------------------------------------------------------------------------------------------- |
|-| Only copy files that did not exist in the parent of the working directory.                  | 
|-| Only copy files that were newer than the versions in the parent of the working directory.   |
|-| You can consider that all HTML files have the extension .html.                              |

<br>   

> 📝 **Footnotes :** 

`cp` - copy files and directories

<h5> Optional Flags & Descriptions <h5>

       -a, --archive
              same as -dR --preserve=all

       --attributes-only
              don't copy the file data, just the attributes

       --backup[=CONTROL]
              make a backup of each existing destination file

       -b     like --backup but does not accept an argument

       --copy-contents
              copy contents of special files when recursive

       -d     same as --no-dereference --preserve=links

       -f, --force
              if an existing destination file cannot be opened, remove
              it and try again (this option is ignored when the -n
              option is also used)

       -i, --interactive
              prompt before overwrite (overrides a previous -n option)

       -H     follow command-line symbolic links in SOURCE

       -l, --link
              hard link files instead of copying

       -L, --dereference
              always follow symbolic links in SOURCE

       -n, --no-clobber
              do not overwrite an existing file (overrides a previous -i
              option)

       -P, --no-dereference
              never follow symbolic links in SOURCE

       -p     same as --preserve=mode,ownership,timestamps

       --preserve[=ATTR_LIST]
              preserve the specified attributes (default:
              mode,ownership,timestamps), if possible additional
              attributes: context, links, xattr, all

       --no-preserve=ATTR_LIST
              don't preserve the specified attributes

       --parents
              use full source file name under DIRECTORY

       -R, -r, --recursive
              copy directories recursively

       --reflink[=WHEN]
              control clone/CoW copies. See below

       --remove-destination
              remove each existing destination file before attempting to
              open it (contrast with --force)

       --sparse=WHEN
              control creation of sparse files. See below

       --strip-trailing-slashes
              remove any trailing slashes from each SOURCE argument

       -s, --symbolic-link
              make symbolic links instead of copying

       -S, --suffix=SUFFIX
              override the usual backup suffix

       -t, --target-directory=DIRECTORY
              copy all SOURCE arguments into DIRECTORY

       -T, --no-target-directory
              treat DEST as a normal file

       -u, --update
              copy only when the SOURCE file is newer than the
              destination file or when the destination file is missing

       -v, --verbose
              explain what is being done

       -x, --one-file-system
              stay on this file system

       -Z     set SELinux security context of destination file to
              default type

       --context[=CTX]
              like -Z, or if CTX is specified then set the SELinux or
              SMACK security context to CTX

       --help display this help and exit

       --version
              output version information and exit
  
  <br>
   
> 📁 **15. Let’s move**
> 
> 💾 **File :** [100-lets_move](./100-lets_move)
> 
> 📑 **Task :**: A script that moves all files beginning with an uppercase letter to the directory /tmp/u.
> 
> 📝 **Required :** 

<br>

| | Guides                                                                                      |
|-| ------------------------------------------------------------------------------------------- |
|-| You can assume that the directory /tmp/u will exist when we will run your script            | 

<br> 
  
> 📝 **Footnotes :** 
  
<h5> Bash </h5>
  
<br>
  
> `^` to convert the first letter to uppercase and ^^ to convert all characters to uppercase.

> `,` to convert the first letter to lowercase and ,, to convert all characters to lowercase.

> `~` to toggles the case for the first character and ~~ to toggle cases for all characters.

<h5> POSIX </h5>

Note : (Portable Operating System Interface) is a set of standard operating system interfaces based on the Unix operating system.
  
> If you are looking for portability, use the tr command with [:lower:] and [:upper:].
>
> The tr command translates characters by using it with character classes. 
>
> You can use a character class using the syntax [:class:] where class is one of the POSIX character classes.
  
<h5> POSIX character classes </h5>
  
> `alnum:` Alphanumeric characters [:alpha:] and [:digit:]
>
> `blank:` Space and tag
>
> `digit:` 0-9
>
> `lower:` Lowercase letters
>
> `punct:` Punctuation characters
>
> `upper:` Uppercase letters
>
> `alpha:` Alphabetic characters [:lower:] and [:upper:]
>
> `cntrl:` Control characters
>
> `graph:` Graphic characters [:alnum:] and [:punct:]
>
> `print:` Printable characters
>
> `space:` Space characters
>
> `xdigit:` Hexadecimal digits 0-9 A-F a-f
  
<br>
 
> 📁 **16. Clean Emacs**
> 
> 💾 **File :** [101-clean_emacs](./101-clean_emacs)
> 
> 📑 **Task :**: A script that deletes all files in the current working directory that end with the character ~.
> 
<br>  
  
> 📁 **17. Tree**
> 
> 💾 **File :** [102-tree](./102-tree)
> 
> 📑 **Task :** A script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
>
> 📝 **Required :** 

<br>

| | Guides                                                                             |
|-| ---------------------------------------------------------------------------------- |
|-| You are only allowed to use two spaces (and lines) in your script, not more        | 

<br> 
 
> 📁 **18. Life is a series of commas, not periods**
> 
> 💾 **File :** [103-commas](./103-commas)
> 
> 📑 **Task :** A command that lists all the files and directories of the current directory, separated by commas (,).
>   
> 💬 *Quote : "Life is a series of commas, not periods." - Matthew McConaughey*
>
> 📝 **Required :**

<br>

| | Guides                                                                                                          |
|-| --------------------------------------------------------------------------------------------------------------- |
|-| Directory names should end with a slash (/)                                                                     | 
|-| Files and directories starting with a dot (.) should be listed                                                  |
|-| The listing should be alpha ordered, except for the directories . which should be listed at the very beginning  |
|-| The listing should be alpha ordered, except for the directories .. which should be listed at the very beginning |
|-| Only digits and letters are used to sort; Digits should come first                                              | 
|-| You can assume that all the files we will test with will have at least one letter or one digit                  |
|-| The listing should end with a new line                                                                          |

<br>  
  
> 📝 **Footnotes :** 

`ls` - list directory contents

<h5> Optional Flags & Descriptions <h5>

       -a, --all
              do not ignore entries starting with .

       -A, --almost-all
              do not list implied . and ..

       --author
              with -l, print the author of each file

       -b, --escape
              print C-style escapes for nongraphic characters

       --block-size=SIZE
              with -l, scale sizes by  SIZE  when  printing  them;  e.g.,
              '--block-size=M'; see SIZE format below

       -B, --ignore-backups
              do not list implied entries ending with ~

       -c     with  -lt: sort by, and show, ctime (time of last modifica‐
              tion of file status information); with -l: show  ctime  and
              sort by name; otherwise: sort by ctime, newest first

       -C     list entries by columns

       --color[=WHEN]
              colorize the output; WHEN can be 'always' (default if omit‐
              ted), 'auto', or 'never'; more info below

       -d, --directory
              list directories themselves, not their contents

       -D, --dired
              generate output designed for Emacs' dired mode

       -f     do not sort, enable -aU, disable -ls --color

       -F, --classify
              append indicator (one of */=>@|) to entries

       --file-type
              likewise, except do not append '*'

       --format=WORD
              across -x, commas -m, horizontal -x, long -l, single-column
              -1, verbose -l, vertical -C

       --full-time
              like -l --time-style=full-iso

       -g     like -l, but do not list owner

       --group-directories-first
              group directories before files;

              can  be  augmented  with  a  --sort  option, but any use of
              --sort=none (-U) disables grouping

       -G, --no-group
              in a long listing, don't print group names

       -h, --human-readable
              with -l and -s, print sizes like 1K 234M 2G etc.

       --si   likewise, but use powers of 1000 not 1024

       -H, --dereference-command-line
              follow symbolic links listed on the command line

       --dereference-command-line-symlink-to-dir
              follow each command line symbolic link

              that points to a directory

       --hide=PATTERN
              do not list implied entries matching shell  PATTERN  (over‐
              ridden by -a or -A)

       --hyperlink[=WHEN]
              hyperlink  file  names;  WHEN  can  be 'always' (default if
              omitted), 'auto', or 'never'

       --indicator-style=WORD
              append indicator with  style  WORD  to  entry  names:  none
              (default),  slash  (-p),  file-type (--file-type), classify
              (-F)

       -i, --inode
              print the index number of each file

       -I, --ignore=PATTERN
              do not list implied entries matching shell PATTERN

       -k, --kibibytes
              default to 1024-byte blocks for disk usage; used only  with
              -s and per directory totals

       -l     use a long listing format

       -L, --dereference
              when  showing  file  information  for a symbolic link, show
              information for the file the link  references  rather  than
              for the link itself

       -m     fill width with a comma separated list of entries

       -n, --numeric-uid-gid
              like -l, but list numeric user and group IDs

       -N, --literal
              print entry names without quoting

       -o     like -l, but do not list group information

       -p, --indicator-style=slash
              append / indicator to directories

       -q, --hide-control-chars
              print ? instead of nongraphic characters

       --show-control-chars
              show  nongraphic characters as-is (the default, unless pro‐
              gram is 'ls' and output is a terminal)

       -Q, --quote-name
              enclose entry names in double quotes

       --quoting-style=WORD
              use quoting style WORD for entry  names:  literal,  locale,
              shell,  shell-always, shell-escape, shell-escape-always, c,
              escape (overrides QUOTING_STYLE environment variable)

       -r, --reverse
              reverse order while sorting

       -R, --recursive
              list subdirectories recursively

       -s, --size
              print the allocated size of each file, in blocks

       -S     sort by file size, largest first

       --sort=WORD
              sort by WORD instead of name: none (-U),  size  (-S),  time
              (-t), version (-v), extension (-X)

       --time=WORD
              change the default of using modification times; access time
              (-u): atime, access, use; change time (-c): ctime,  status;
              birth time: birth, creation;

              with   -l,   WORD  determines  which  time  to  show;  with
              --sort=time, sort by WORD (newest first)

       --time-style=TIME_STYLE
              time/date format with -l; see TIME_STYLE below

       -t     sort by time, newest first; see --time

       -T, --tabsize=COLS
              assume tab stops at each COLS instead of 8

       -u     with -lt: sort by, and show, access  time;  with  -l:  show
              access  time  and  sort  by name; otherwise: sort by access
              time, newest first

       -U     do not sort; list entries in directory order

       -v     natural sort of (version) numbers within text

       -w, --width=COLS
              set output width to COLS.  0 means no limit

       -x     list entries by lines instead of by columns

       -X     sort alphabetically by entry extension

       -Z, --context
              print any security context of each file

       -1     list one file per line.  Avoid '\n' with -q or -b

       --help display this help and exit

       --version
              output version information and exit
  
  <br>
  
> 📁 **19. File type: School**
> 
> 💾 **File :** [school.mgc](./school.mgc)
> 
> 📑 **Task :** A magic file school.mgc that can be used with the command file to detect School data files.
> 
> 📝 **Required :** 

<br>

| | Guides                                                               |
|-| -------------------------------------------------------------------- |
|-| School data files always contain the string SCHOOL at offset 0.      |
  
> 📝 **Footnotes :** 

> The magic file contains lines describing magic numbers, which identify particular types of files. 
>
> Lines beginning with a `>` or `&` character represent continuation lines to a preceding main entry: `>` 
>
>If the file command finds a match on the main entry line, these additional patterns are checked.
