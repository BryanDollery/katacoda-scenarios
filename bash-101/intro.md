# bash-101: An introduction to Bash
## A hit-the-ground-running approach to teaching bash
### Try to keep up


#### What is a shell?
In Linux, a shell is a command intepreter: a program that has the permission and ability to run other programs. On Linux it is possible to run many sessions, or instances, of a shell simultaneously.

#### What is bash?
Bash is a program that has the capabilities and permissions to run other programs. It is the result of decades of evolution and is highly sophisticated though is often mired in the past. It is one of the most highly developed and efficient methods of interacting with a computer. But, it is really reserved for people who deeply understand computers and who understand why a lot of things are better done with a keyboard than a mouse.


There are plenty of other shells that we could learn about, some of them are considered 'better' than bash (`fish`, for example, is excellent), for one technical reason or another (or many). But, bash is ubiquitous and is considered the reference point for a lot of other work. When you look at a shell-script it is 10x more likely to be a bash script than any other. Of special note here is 'sh' the base shell installed with most Linux distributions. A lot of scripts target that environment because it is even more widespread than bash. But, it lacks a lot of bash's sophistication and in reality can be ignored. Coding for `sh` rather than `bash` is hip and therefore you can forget it. Target Bash and you'll be ok.

There are two fundamental methods of working with bash: Terminals and Scripts

Terminals, sometimes called command-lines, sessions, or, confusingly, shells, exist for people: they hold the user-interface for a shell. Scripts are lists of bash instructions in a file that execute either in the current shell or in a new one. 

#### What will you learn?
At first we'll look at terminals, but we'll quickly move into scripts too. You'll learn a bunch of useful skills in a terminal and how to use bash, even though right now you won't learn that many commands. That's what the rest of the course is for.
