# scripts

## emv
Uses EDITOR to edit a file name or group of file names, e.g. if the file `example.txt` is in the current dir, `emv example.txt` will pop up your favorite editor with the filename in it, then will move the file to the new name on save and quit. You can do multiple files at once.

Caveat: You cannot swap file names.

## genpasswd
Generates a random password using letters, numbers, and special characters. Options include:
* -l _length_: Sets the length of the resulting password
* -h: Print the md5 hash of the password on the next line
