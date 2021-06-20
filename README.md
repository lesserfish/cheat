# cheat
A simple tool to write and read descriptions about whatever you want


Cheat is for cheat-sheet. Basically a more simple version of man, which you usually update by yourself.
Usage is as follows: "
 
    cheat [command] [paramaters]

List of commands:
read - parameter [0] will be read.
write - Creates a new file with the parameter being a text file containing the information to be displayed. Parameters are [0] = File to be added
update - Appends file [1] to the existent file [0], or [0] to [0] if [1] is not specified
destroy - Destroys file [0]
recreate" - Destroys the file [0] and creates file [1] with the same name, or [0] if [1] is not specified
