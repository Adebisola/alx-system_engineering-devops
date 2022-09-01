!/bin/bash-tells the bash to execute
pwd-Prints the present working directory
ls-prints the content of the working directory
cd-changes the working directory to the user's home directory
ls -l-it display the current directory content in long format
ls -al- lists all the files in the working dieerctory even the hidden ones
ls -aln- lists the pwd in long format, displays the user and group IDs numerically,shows hidden files
mkdir /tmp/my_first_directory creates a directory in another directory
cd - changes the working directory to the previous one
mv /tmp/betty/tmp/my_first_directory will move Betty in my first directory
rm /tmp/my_first_directory will delete betty
rm -r /tmp/my-first_directory will delete my_first_directory RET
ls -al . .. /boot will list all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format. RET
file /tmp/iamafile will Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your scriptls -al . .. /boot writes a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile writes a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
cp -rua *.hmtl ../ Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
 mv [[:upper:]]* /tmp/u will create a script that moves all files beginning with an uppercase letter to the directory /tmp/
rm *~ creates a script that deletes all files in the current working directory that end with the character ~.
mkdir -p welcome/to/school creates  a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory
0 string SCHOOL School data will create  a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0
