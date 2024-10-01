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
[Animation](https://github.com/user-attachments/assets/7868c36a-e1ba-49be-87aa-5ce06ce3e61a)

./mkscript.sh my_script
This will create a file named my_script.sh, make it executable, add a shebang line, and open it in mousepad.

# Options
<script_name>: The name for the new script. If the .sh extension is not provided, it will be added automatically.

# Prerequisites
Bash: Ensure that Bash is installed and accessible in your system.
mousepad: The script uses mousepad to open the created file. You can modify the script to use your preferred text editor if mousepad is not available.

# Installation
Clone the repository to your local machine:

git clone https://github.com/0Reab/bash-script-creator.git
Navigate to the script directory:

cd bash-script-creator
Make the script executable:

chmod +x mkscript.sh

# Notes
Ensure that the target filename does not conflict with existing files in the directory to avoid accidental overwriting.
You can customize the script to use a different text editor by changing the mousepad command in the script.
Contributing
Feel free to fork this repository and submit pull requests if you have any improvements or additional features you'd like to add. :D
