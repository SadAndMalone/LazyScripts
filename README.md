# Scripts to Make My Life Less Miserable

This will one day contain all of the scripts that I use to make mundane tasks easier.

## How to Use These Scripts

Clone the repository (or don't you can just download the files individually).
Move the file into a directory that is in your $PATH.
```
$ echo $PATH
```
If you want to create a special directory for these (I'll use bin in the example)
```
$ export PATH=$PATH:/home/$USER/bin
```
The script can now be run from anywhere by just typing the name of the script.

Using adding the above command to ~/.bashrc will run it everytime you start.

## HTML Skeleton

### File Name: htmlinit

### Function

Creates a base skeleton of an empty html file:
```
<!doctype html>
<html>
	<head>
		<title></title>
	</head>
	<body>
	</body>
</html>
```

### Usage
There is no way to mess it up, just running it will just output it to the terminal.
Simply pipe the output into the file you wish to generate.
The following command will create a file called sample.html, and send its output there.
```
$ htmlinit >> sample.html
```
