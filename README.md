# Bash-script-creator
This Bash script is designed to quickly and efficiently create new Bash scripts with executable permissions and a shebang line. It also ensures that the script file opens in a mousepad immediately after creation for easy start.

# Features
Automatic Shebang Line: Adds a #!/bin/bash line to the new script, ensuring it runs with Bash.
Executable Permissions: Automatically sets executable permissions on the new script file.
Filename Handling: Ensures the script filename has a .sh extension.
Error Handling: Provides clear error messages and prevents overwriting existing files.
Background Editing: Opens the newly created script in the mousepad text editor.
Usage
To use the script, run it with the desired name for your new Bash script as an argument. Optionally, you can add a verbosity flag -v to get detailed output.

# Basic Usage

./mkscript.sh <script_name>

# Efficient Usage

Put this script in /usr/local/bin and remove '.sh' extension so you can run this globally and without './'
cp mkscript.sh mkscript
sudo mv mkscript /usr/local/bin

# Example!
![Alt Text](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExbGtmNnA1bjJwamxvbTk4NnBsY25qeHh2b2c5NGNxNzNsZGZmOWw3biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/bvkTppcJO3mf7uw1qu/giphy.gif)

./mkscript.sh my_script
This will create a file named my_script.sh, make it executable, add a shebang line, and open it in vim.

# Options
<script_name>: The name for the new script. If the .sh extension is not provided, it will be added automatically.

# Installation
Clone the repository to your local machine:

git clone https://github.com/0Reab/bash-script-creator.git
Navigate to the script directory:

cd bash-script-creator
Make the script executable:

chmod +x mkscript.sh

# Notes
The script will not overwrite if filename conflicts with existing files in the directory but don't test your luck :D.
You can customize the script to use a different text editor by changing the vim command in the script.
Contributing
Feel free to fork this repository and submit pull requests if you have any improvements or additional features you'd like to add. :D
