# README

### Bitmap Files
If you need a bitmap file to test with you can download one of the files above.

### Compiling
Use the supplied makefile by by typing ```make``` in the terminal.

### Running
To run in interactive mode:
```
./main.out
```

To run in admin mode:
```
./main.out -admin
```
The admin password is:
```
1234
```
Admin mode will list all usernames and passwords in the database.

### Add a user

On first run you will need to make a new user by pressing "2". Then you can login by pressing "1".
You may create as many users as you like.

### Create a Message

After logging in press "1" to create a new message. You will need a bitmap file - it can be anywhere on your
computer but much easier if its in the working directory.

Follow the onscreen instructions providing a bitmap filename ane type in a message to encrypt.

You will be shown your encrypted message on screen and the name of the output file.
The output filename will be appeneded with an extension:
### _enc

### Read a Message

After logging in press "2" to decrypt a bitmap message you have recieved. It will most likely be a file with:
### _enc
on the end.
Supply the name of the file and the decrypted message will be displayed on the screen.

