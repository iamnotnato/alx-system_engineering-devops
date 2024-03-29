> 🚧 **Project :** 0x03-shell_variables_expansions

<br>

> 📝 **Summary:**

> These are projects that helped me understand bash scripting.

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

> 📁 **0. <o>**
>
> 💾 **File :** [0-alias](./0-alias)
>
> 📑 **Task :** A script that creates an alias.
>
> 📝 **Required :** 

<br>

| | Guides    |
|-| --------- |
|-| Name: ls  |
|-| Value: rm |

> 📝 ** Note :** 

> Linux 'alias' command replaces one string from the shell with another string. It is a shell built-in command.
>
> It converts a complicated command into a simpler command or in other words, it creates a shortcut by replacing it with the simpler one.
>
> Making 'alias' in command line creates a temporary 'alias'.
>
<br> 
 
> 📁 **1. Hello you**
>
> 💾 **File :** [1-hello_you](./1-hello_you)
>
> 📑 **Task :** A script that prints hello user, where user is the current Linux user.
>
<br>  
 
> 📁 **2. The path to success is to take massive, determined action**
>
> 💾 **File :** [2-path](./2-path)
>
> 📑 **Task :** Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
>
> 💬 *Quote : The path to success is to take massive, determined action. - Tony Robbins* 
>
<br>

> 📁 **3. If the path be beautiful, let us not ask where it leads**
>
> 💾 **File :** [3-paths](./3-paths)
>
> 📑 **Task :** A script that counts the number of directories in the PATH.
>
> 💬 *Quote : Anatole France — 'If the path be beautiful, let us not ask where it leads.'* 
>  
<br>
 
> 📁 **4. Global variables**
>
> 💾 **File :** [4-global_variables](./4-global_variables)
>
> 📑 **Task :** A script that lists environment variables.
>
> 📝 **Notes :** 

> In Linux and Unix based systems environment variables are a set of dynamic named values, stored within the system that are used by applications launched in shells or subshells.
>
> In simple words, an environment variable is a variable with a name and an associated value.
>
> Environment variables allow you to customize how the system works and the behavior of the applications on the system.
>
<br>   
   
> 📁 **5. Local variables**
>
> 💾 **File :** [5-local_variables](./5-local_variables)
>
> 📑 **Task :** A script that lists all local variables and environment variables, and functions.
>
<br> 
 
> 📁 **6. Local variable**
>
> 💾 **File :** [6-create_local_variable](./6-create_local_variable)
>
> 📑 **Task :** A script that creates a new local variable.
>
> 📝 **Required :** 

<br>

| | Guides        |
|-| ------------- |
|-| Name: BEST    |
|-| Value: School |

<br>   
   
> 📁 **7. Global variable**
>
> 💾 **File :** [7-create_global_variable](./7-create_global_variable)
>
> 📑 **Task :** A script that creates a new global variable.
>
> 📝 **Required :** 

<br>

| | Guides        |
|-| ------------- |
|-| Name: BEST    |
|-| Value: School |

<br> 
 
> 📁 **8. Every addition to true knowledge is an addition to human power**
>
> 💾 **File :** [8-true_knowledge](./8-true_knowledge)
>
> 📑 **Task :** A script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
>
> 💬 *Quote : Every addition to true knowledge is an addition to human power.“ - Horace Mann.*
>
<br>

> ✔️ Sample test cases :

```
~$ export TRUEKNOWLEDGE=1209
~$ ./8-true_knowledge | cat -e
1337$
~$
```
<br>

> 📁 **9. Divide and rule**
>
> 💾 **File :** [9-divide_and_rule](./9-divide_and_rule)
>
> 📑 **Task :** A script that prints the result of POWER divided by DIVIDE, followed by a new line.
>
> 💡*Fun Fact : Divide and rule policy, or divide and conquer, in politics and sociology is gaining and maintaining power divisively.*
>
> *Historically, this strategy was used in many different ways by empires seeking to expand their territories.* 
>
> 📝 **Required :** 

<br>

| | Guides                                     |
|-| ------------------------------------------ |
|-| POWER and DIVIDE are environment variables |

<br>

> ✔️ Sample test cases :

```
~$ export POWER=42784
~$ export DIVIDE=32
~$ ./9-divide_and_rule | cat -e
1337$
~$
```
<br>

> 📁 **10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath**
>
> 💾 **File :** [10-love_exponent_breath](./10-love_exponent_breath)
>
> 📑 **Task :** A script that displays the result of BREATH to the power LOVE
>
> 💬 *Quote : Love is anterior to life, posterior to death, initial of creation, and the exponent of breath. - Emily Dickinson* 
>
> 📝 **Required :** 

<br>

| | Guides        |
|-| ------------- |
|-| BREATH and LOVE are environment variables  |
|-| The script should display the result, followed by a new line |

<br>

> ✔️ Sample test cases :

```
~$ export BREATH=4
~$ export LOVE=3
~$ ./10-love_exponent_breath
64
~$
```
<br>

> 📁 **11. There are 10 types of people in the world -- Those who understand binary, and those who don't**
>
> 💾 **File :** [11-binary_to_decimal](./11-binary_to_decimal)
>
> 📑 **Task :** A script that converts a number from base 2 to base 10.
>
> 😂 *Joke : “There are only 10 types of people in the world: those who understand binary and those who don’t.” — Unknown.* 
>
> 📝 **Required :** 

<br>

| | Guides                                                                 |
|-| ---------------------------------------------------------------------- |
|-| The number in base 2 is stored in the environment variable BINARY      |
|-| The script should display the number in base 10, followed by a new line|

<br>

> ✔️ Sample test cases :

```
~$ export BINARY=10100111001
~$ ./11-binary_to_decimal
1337
~$
```
<br>

> 📁 **12. Combination**
>
> 💾 **File :** [12-combinations](./12-combinations)
>
> 📑 **Task :** A script that prints all possible combinations of two letters, except oo.
>
> 📝 **Required :** 

<br>

| | Guides                                                  |
|-| ------------------------------------------------------- |
|-| Letters are lower cases, from a to z                    | 
|-| One combination per line                                |
|-| The output should be alpha ordered, starting with aa    | 
|-| Do not print oo                                         |
|-| Your script file should contain maximum 64 characters   |

<br>

> ✔️ Sample test cases :

```
~$ echo $((26 ** 2 -1))
675
~$ ./12-combinations | wc -l
675
~$
~$ ./12-combinations | tail -303 | head -10
oi
oj
ok
ol
om
on
op
oq
or
os
~$ 
```
<br>
  
> 📁 **13. Floats**
>
> 💾 **File :** [13-print_float](./13-print_float)
>
> 📑 **Task :** A script that prints a number with two decimal places, followed by a new line.
>
> 📝 **Required :** 

<br>

| | Guides                                                        |
|-| ------------------------------------------------------------- |
|-| The number will be stored in the environment variable NUM.    |

<br>

> ✔️ Sample test cases :

```
~$ export NUM=0
~$ ./13-print_float
0.00
~$ export NUM=98
~$ ./13-print_float
98.00
~$ export NUM=3.14159265359
~$ ./13-print_float
3.14
~$
```
<br>
 
> 📁 **14. Decimal to Hexadecimal**
>
> 💾 **File :** [100-decimal_to_hexadecimal](./100-decimal_to_hexadecimal)
>
> 📑 **Task :** A script that converts a number from base 10 to base 16.
>
> 📝 **Required :** 

<br>

| | Guides                                                        |
|-| ------------------------------------------------------------- |
|-| The number in base 10 is stored in the environment variable DECIMAL    |
|-| The script should display the number in base 16, followed by a new line  |

<br>

> ✔️ Sample test cases :

```
~$ export DECIMAL=16
~$ ./100-decimal_to_hexadecimal
10
~$ export DECIMAL=1337
~$ ./100-decimal_to_hexadecimal | cat -e
539$
~$ export DECIMAL=15
~$ ./100-decimal_to_hexadecimal | cat -e
f$
~$
```
<br>
   
> 📁 **15. Everyone is a proponent of strong encryption**
>
> 💾 **File :** [101-rot13](./101-rot13)
>
> 📑 **Task :** A script that encodes and decodes text using the rot13 encryption. Assume ASCII.
>
> 💬 *Quote : Everyone is a proponent of strong encryption. - Dorothy Denning* 
>
> 📝 **Notes :** 
  
> ROT13 ("rotate by 13 places", sometimes hyphenated ROT-13) is a simple letter substitution cipher that replaces a letter with the 13th letter after it in the alphabet.
>
> ROT13 is a special case of the Caesar cipher which was developed in ancient Rome.

<br>

> ✔️ Sample test cases :

```
~$ cat quote
"Everyone is a proponent of strong encryption."
- Dorothy E. Denning
~$ ./101-rot13 < quote
"Rirelbar vf n cebcbarag bs fgebat rapelcgvba."
- Qbebgul R. Qraavat
~$
```
<br>
 
> 📁 **16. The eggs of the brood need to be an odd number**
>
> 💾 **File :** [102-odd](./102-odd)
>
> 📑 **Task :** A script that prints every other line from the input, starting with the first line.
>
> 🦉 *Proverb : The eggs of the brood need to be an odd number. Sicilian Proverbs*
>
<br>

> 📁 **17. I'm an instant star. Just add water and stir.**
>
> 💾 **File :** [103-water_and_stir](./103-water_and_stir)
>
> 📑 **Task :** A shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result.
>
> 💬 *Quote : "I'm an instant star. Just add water and stir." - David Bowie*
>
> 📝 **Required :** 

<br>

| | Guides                                  |
|-| --------------------------------------- |
|-| WATER is in base water                  | 
|-| STIR is in base stir.                   |
|-| The result should be in base bestchol   | 

<br>

> ✔️ Sample test cases :

```
~$ export WATER="ewwatratewa"
~$ export STIR="ti.itirtrtr"
~$ ./103-water_and_stir
shtbeolhc
~$
```
<br>
