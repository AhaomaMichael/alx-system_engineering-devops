pwd -prints the absolute path name of the current working directory
ls -display the contents list of your current directory
cd -write a script that changes the working directory to the user’s home directory
ls -l -display current directory contents in a long format
ls -all -display current directory contents, including hidden files (starting with .). Use the long format
ls -all -n -display current directory contents in long format, with user and group IDs displayed numerically and hidden files (starting with .)
mkdir /tmp/my_first_directory -create a script that creates a directory named my_first_directory in the /tmp/ directory
mv /tmp/betty /tmp/my_first_directory/betty -move the file betty from /tmp/ to /tmp/my_first_directory
rm /tmp/my_first_directory/betty -delete the file betty
rm -r /tmp/my_first_directory -delete the directory my_first_directory that is in the /tmp directory
cd - -a script that changes the working directory to the previous one
ls -la . .. /boot -a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
file /tmp/iamafile -script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script
ln -s /bin/ls __ls__ -symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory
cp *.html ../ -a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
mv [A-Z]* /tmp/u -a script that moves all files beginning with an uppercase letter to the directory /tmp/u
rm *~ -a script that deletes all files in the current working directory that end with the character ~
mkdir -p welcome/to/school -a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory
ls -map -a command that lists all the files and directories of the current directory, separated by commas (,)
 


