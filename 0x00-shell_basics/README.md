#**Shell  Basics**

**pwd -P** print working directory

**ls** lists directory contents

**cd** changes directory

**ls -l** lists directory contents in long form

**ls -la** lists directory contents in long form, including hidden files

**mkdir /tmp/school** Creates a holberton directory inside the tmp directory

**mv /tmp/betty /tmp/holberton/betty** Moves file betty, which is located inside the tmp directory, to the holberton directory, which is also located inside the tmp directory.

**rm /tmp/holberton/betty** Removes file betty located in tmp/holberton directory.

**rmdir /tmp/holberton// Removes directory holberton located in directory tmp.

**cd -** Changes directory to the previous directory you were in.

**ls -la . .. /boot** Lists all files/directories, including hidden files/directories, from 3 separate directories: current directory, parent of working directory, and /boot directory. The ls command allows multiple directories to be listed separated by spaces.

**file /tmp/iamafile** Prints the type of file iamafile.

**ln -s /bin/ls _ls_** Creates a symbolic link named ls for /bin/ls

cp -u *.html .. **Copies all html files from the current directory to the parent directory, but only copy files that didn't exist in the parent directory or are newer versions than the ones that already exist in the parent directory. The -u option didn't show on the terminal manual page. The -u option copies the file into the directory if its a newer version. If the file doesn't exist in the directory, it will copy over. The -n option works for copying files that don't exist in the parent directory, but it doesn't check if the file is a newer version or not.**

mv [[:upper:]]* /tmp/u **Moves all files that begin with a capital letter to /tmp/u**

rm *~ **Deletes all files in the current directory that end with a ~**

**mkdir -p welcome/to/holberton** Creates directory welcome in current directory. Create directory to inside directory welcome. Create directory holberton inside directory to. The -p option creates any intermediate directories in the path argument.

**ls -pam** List all files and directories of the current directory, separated by commas. Directory names should end with a /. The listing should be alph ordered, except for dot (.) or dot dot (..), which should be listed at the beginning. The -a option is to show any hidden files. The -p option writes a / at the end of directory names. The -m option streams the output, separating each listing with commas.

**0 string SCHOOL School data !:mime School** Creates a magic file called school.mgc that can be used with the command file to detect school data files. School on data files always contain "SCHOOL" at offset 0.
