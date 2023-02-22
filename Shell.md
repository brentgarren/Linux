## Shell

A Linux terminal, also called a shell or command line, provides a text-based input/output (I/O) interface between users and the kernel for a computer system. 
The term console is also typical but does not refer to a window but a screen in text mode. In the terminal window, commands can be executed to control the system.
<br>
The bash prompt is easy to understand and, by default, includes information such as the user, hostname, and current working directory. The format can look something like this:
<pre>
<username>@<hostname><current working directory>$
</pre>
<br>
The home directory is marked with a <~> and is the home directory for when we log in
<pre>
<username>@<hostname>[~]$
</pre>
The Dolllar sign stands for user, As soon as we log in to root it changes to a #
<pre>
root@htb[/htb]#
</pre>
<br>
For example, when we upload and run a shell on the target system, we may not see the username, hostname, and current working directory. 
This may be due to the PS1 variable in the environment not being set correctly. In this case, we would see the following prompts:

<pre>
Unpriveleged User Shell prompt
$
</pre>
<pre>
Priveleged User Shell Prompt
#
</pre>
