<div align="center">
<img height="125" src="assets/overkill.png">
</div>

<h1 align="center">autoshell🐚</h1>

> A quicker way to fire up my projects with gitbash 🚀

## openGit.sh 🐚

>This Bash script allows you to easily open Git Bash in a specified directory on a Windows machine. The script uses the ``cd`` command to change to the desired directory and then runs the ``start`` command to launch Git Bash with the ``git-bash.exe`` executable.
>The script is currently configured to work on a Windows machine, but it can be modified to work on other operating systems as well. Simply change the value of the ``DIR`` variable to point to the desired directory.
>To use the script, save it as a file with a ``.sh`` extension and run it from the command line with bash ``<script_name>.sh``.

## openGit.ps1 🪟

This PowerShell script allows you to easily open Git Bash in a specified directory on a Windows machine. The script uses the ``Set-Location`` command to change to the desired directory and then runs the ``Start-Process`` command to launch Git Bash with the ``git-bash.exe`` executable.

The script is currently configured to work on a Windows machine, but it can be modified to work on other operating systems as well. Simply change the value of the ``$directory`` and ``$git`` variables to point to the desired directory and Git Bash executable, respectively.

To use the script, save it as a file with a .ps1 extension and run it from the PowerShell command line with ``.\<script_name>.ps1``.