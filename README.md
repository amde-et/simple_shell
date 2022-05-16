#simple shell partner project

[ALX School C Programming-group project](https://github.com/corbinenterline1/simple_shell.git)

## The folder contains the group project "simple_shell" and associated tasks:
00. Folder contents (28 functions, 1 header)
	* prompt.c
		* main program
		* spacecheck
		* _atoi
	* read_input.c
		* read_input
		* env_print
		* pathandfree
		* _halt
		* freeptrarrayandexit
	* errortime.c
		* errortime
		* _abs
		* _reverse
		* _swap
		* _itoa
	* newlistnewnode.c
		* pathchecker
		* pathlist
		* add_node
		* createpathlist
		* free_list
	* supp_functions.c
		* _strncpy
		* _strlen
		* _putchar
		* _strncmp
		* str_concat
	* supp_functions02.c
		*  
0. README, man, AUTHORS - repo: simple_shell, README.md, man_1_simple_shell, AUTHORS
	* Write a README
	* Write a man for your shell.
	* You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository.
1. Betty would be proud
	* Write a beautiful code that passes the Betty checks
3. Simple shell 0.1
	* Write a UNIX command line interpreter.
		Your shell should:
		* Display a prompt and wait for the user to type a command. A command line always ends with a new line.
		* The prompt is displayed again each time a command has been executed.
		* The command lines are simple, no semicolons, no pipes, no redirections or any other advanced features.
		* The command lines are made only of one word. No arguments will be passed to programs.
		* If an executable cannot be found, print an error message and display the prompt again.
		* Handle errors.
		* You have to handle the end of file condition (Ctrl+D)
5. Simple shell 0.2
	* Simple shell 0.1+
		* Handle command lines with arguments
7. Simple shell 0.3
	* Simple shell 0.2+
		* Handle the PATH
8. Simple shell 0.4
	* Simple shell 0.3+
		* Implement the exit built-in, that exits the shell
		* Usage: exit
		* You dont have to handle any argument to the built-in exit
11. Simple shell 1.0
	* Simple shell 0.4+
		* Implement the env built-in, that prints the current environment
22. What happens when you type ls-l in the shell - blogpost
	* Write a blog post describing step by step what happens when you type ls -l and hit Enter in a shell. Try to explain every step you know of, going in as much details as you can, give examples and draw diagrams when needed. You should merge your previous knowledge of the shell with the specifics of how it works under the hoods (including syscalls).
		* Have at least one picture, at the top of the blog post
		* Publish your blog post on Medium or LinkedIn
		* Share your blog post at least on LinkedIn
		* Only one blog post by team
		* The blog post must be done and published before the first deadline (it will be part of the manual review)
		* Please, remember that these blogs must be written in English to further your technical ability in a variety of settings
