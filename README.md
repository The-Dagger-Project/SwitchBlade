# SwitchBlade Editor
SwitchBlade is an alternative to the command line text editor VIM. It supports syntax highlighting for Dagger, C, and C++. It also has some more familiar commands for exiting, saving, and searching in files, which makes it easier for beginners to use than VIM. 

## Install
(Currently only supports Linux, we're working on support for Windows and MacOS)
Make sure you have git installed by typing in the terminal:

```bash
git --version
```
Clone this repo:

```bash
git clone https://github.com/The-Dagger-Project/SwitchBlade.git
```
Enter the SwitchBlade directory:

```bash
cd SwitchBlade
```
Build it using make
```bash
make
```
Add the executable to /usr/bin:

```bash
sudo cp sblade /usr/bin
```

And that's all, you now have SwitchBlade installed!

## Use

### New files
After installing, in the terminal, go to the directory where you want to make a file, and type:

```bash
sblade
```

Write down the contents of your file, then pres Ctrl+S to save. Type the name that you want to save your file as, and press enter.

To exit, press Ctrl-Q 3 times

### Existing files
In the terminal, go to the directory where the file you want to edit is located, and type 

```bash
sblade name.extension
```

where "name" is the name of the file, and "extension" is the file's extension. It will then open in the editor.