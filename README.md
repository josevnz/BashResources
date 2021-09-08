# Scripting resources

Learning a scripting language is an intimidating task. It also takes time, because practice is the only way to master a skill propertly and you will need to do and re-do your code to learn (new techniques and from your mistakes).

By the end of this article, you will have:

* A list of online tutorials to sharpen your skills
* Reference guide for Bash scripting
* Best practices to write code and to make it more secure
* And resources to edit and execute Bash scripts when you don't have access to a Linux machine.

This is not a complete guide, but it will serve you as a start point to more resources.

## Online tutorials

Nothing beats like a detailed explanation from someone more experienced, specially if is with examples.

* [Linux config Bash scripting for beginners](https://linuxconfig.org/bash-scripting-tutorial-for-beginners): This is perfect if what you want is to learn the basics, quickly. With examples, dividend by topic.
* [Learn Shell](https://www.learnshell.org/): Very complete, from basic to advanced with lots of examples.
* [Enable sysadmin](https://www.redhat.com/sysadmin/topics/bash): Has many practical articles, like this one. You may find a few of mine there, with [their Open Source code](https://github.com/josevnz). :-D
* [FreeCodeCamp](https://www.freecodecamp.org/news/search/?query=bash): Not only Bash but many other languages. Be prepared to spend days brownsing this one.


## Reference guide

Sometimes you want to learn how to perform a specific task without distractions. Also what is better than the official way of solving things?

As they say RTFM (Read The Fine Manual):

* [GNU Bash Manual](https://www.gnu.org/software/bash/manual/bash.html): This is the bible of bash. With consise examples, organized by topic. You will keep coming back to this guide over and over.

Also if you are on linux you must learn to use the following two commands:

```shell=
# 'The GNU Bash Reference Manual', for 'Bash'
info bash
```

And

```shell=
# bash - GNU Bourne-Again SHell
man bash
```

## Check your Bash code

You want to learn how to write efficient code, avoid common mistakes and also make sure your scripts are secure!. Fear not, there are plenty of resources out there to learn basic and advanced skills:

* [ShellCheck - A shell script static analysis tool](https://github.com/koalaman/shellcheck): You must install this tool. Can be used online but its true power comes when you integrate it with VIM, IntelliJ IDE. You will be surprised how you managed to live without this for so long... 
* [OWASP Command Injection](https://owasp.org/www-community/attacks/Command_Injection): Command injection is commonly used to elevate privileges on scripts or programs that do not sanitize user input. Don't be a victim and learn how to write secure code. Also, on the topic of security, you should learn about a (old, hopefully not relevant anymore) remote vulnerability exploit called [Shellshock](https://owasp.org/www-pdf-archive/Shellshock_-_Tudor_Enache.pdf) and how you may be affected if your version of bash is old or your code doesn't sanitize user input.

## Code repositories

The following repositories contain Bash scripts, written in a way that you can learn specific topics by checking the code. All the code is Open Source and you can copy and paste the examples to learn.

* [Code Repository for Complete Bash Shell Scripting; Published by Packt](https://github.com/PacktPublishing/Complete-Bash-Shell-Scripting-). Really nice repository with examples, organized by topic.
* [This is the repository for all practice script for the Udemy course on Shell Scripting](https://github.com/jayant2014/Bash-Scripting): What is a better way to learn about Bash programming than learning by example. Nicely organized by topic, each script topic is small and self describing.
* [shell-scripting-examples](https://github.com/Md-MamunAbdulKayum/shell-scripting-examples): CookBook of common tasks in Bash (like reading from a property file, or accessing a MySQL database). Worth checking.

Keep in mind than code in repositories like GitHib may contain bugs. Also be very careful not to download and run code as the super user or you may find yourself in a pickle.


## Online code execution

What if you want to try something, but you don't have access to Linux/ Unix? This is less than ideal but can also try a few online resources that have a very nice front end where you can run your scripts.

* [MyCompiler.io](https://www.mycompiler.io/new/bash): Syntax support, run the code from your browser and also supports multiple languages. Very convenient, specially if you don't have access to Linux to test a simple script
* [Bash online compiler](https://rextester.com/l/bash_online_compiler): You can run here bash scripts directly from your browser, with a few restrictions. It has a nice Syntax color support
* [LeetCode](https://leetcode.com/playground/new/empty): Has a nice playground where you can write Bash scripts (and many other languages), and if you want you csn try to solve some of the challenges (paid/ free subscription). 

## Wrap up

We cover several online resources that will help you to become a better programmer. Do not forget also that practice is the best way to learn something, so go ahead and start writting a few scripts!
