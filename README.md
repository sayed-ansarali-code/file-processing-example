# file-processing-example
Example of file processing using Mulesoft flows

# Description:
1. This flow uses File Connector "On New or Updated File" to monitor a directory "D:\temp\src" for any new file.
1. Reads the file name and extracts MRN number from it. Assumes the name pattern to be of the format as this example One-1111.txt
1. Logs the MRN numbr to the console. In the case of file names One-1111.txt or Two-2222.txt, it'll log 1111 and 2222 as MRN numbers respectively.
1. Copies the file to another folder "D:\temp\dest"
