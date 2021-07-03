# cheat
A simple tool to write and read descriptions about whatever you want


 
    Cheat is for cheat-sheet! Usage is as follows:
    cheat [command] [parameter] [file]
    List of commands:
    read [file] - Reads the file
    add [file] [directory] -Adds the file. If directory is not specified, the default will be used.
    rm [option] [path] - If option is -f or not specified, removes the file associated to path. If option is -d removes the specified directory
    append [existing-file] [file] - Appens file tp existing file. If file is not specified, cheat will search for a file of the same name as existing-file.
    update [existing-file] [file] - Replaces existing file with the new file. If file is not specified, cheat will search for a file of the same name as existing-file
    ls [path] - Lists all of the files and directories in directory")
    ll [path] - Lists all of the files and directories in the directory while also printing the first line of each file
    git [git commands] - Performs a git command on the directory of cheat. Please use single quotes instead of double quotes.
