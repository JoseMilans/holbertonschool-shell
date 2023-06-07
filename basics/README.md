To write a script that prints the absolute path name of the current working directory, I used Bash. Here is the script:  #!/bin/bash 
cwd=$(pwd)
echo "Current working directory: $cwd"
