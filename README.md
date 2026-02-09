# Bash-script-creator

This Bash script is designed to quickly and efficiently create new Bash scripts with executable permissions and a shebang line.<br>
It also ensures that the script file opens in a text editor of your choice immediately after the file creation for a quick start.

# Features

Adds the Shebang Line.<br>
Set executable permission for your user.<br>
Adds a file extension to the filename.<br>
Prevents overwriting existing files.<br>
Open the script in your favorite text editor.<br>

# Usage

./mkscript.sh <script_name>

# Efficient Usage

Put this script in your PATH, for eg. /usr/local/bin and remove '.sh' extension so you can run this without './'<br>
`cp mkscript.sh mkscript`
`sudo mv mkscript /usr/local/bin`

# Example!

![Alt Text](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExbGtmNnA1bjJwamxvbTk4NnBsY25qeHh2b2c5NGNxNzNsZGZmOWw3biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/bvkTppcJO3mf7uw1qu/giphy.gif)

./mkscript.sh my_script
This will create a file named my_script.sh, make it executable, add a shebang line, and open it in vim.

# Options

<script_name>: Name for the new script. If the .sh extension is not provided, it will be added automatically.

# Installation

Clone the repository to your local machine:<br>
`git clone https://github.com/0Reab/bash-script-creator.git`<br>
Navigate to the script directory:<br>
`cd bash-script-creator`<br>
Make the script executable:<br>
`chmod +x mkscript.sh`

# Notes

Customize the script to use your text editor.<br>
