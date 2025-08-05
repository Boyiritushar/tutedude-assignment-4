# tutedude-assignment-4

Code 1: Read an Existing File Successfully
Description:
This code block:

Creates a file named sample.txt and writes three lines of text to it.

Then opens the same file in read mode and prints its content.

Uses a try-except block to handle the case where the file might not exist, though in this case it always exists.

What it teaches:
Writing to a file using open(..., "w")

Reading a file using open(..., "r")

Using try-except to catch file-related errors.



code 2 :Handle File Not Found Error
📄 Description:
This block:

Writes content to sample.txt.

Then tries to read from a non-existent file called sample1.txt.

Since sample1.txt does not exist, the FileNotFoundError is triggered, and the message "file not found" is printed.



Code 3: Append to a File and Read Final Content
Description:
This code block:

Creates a file named output.txt and writes three lines to it.

Then opens the same file in append mode ("a") and adds "welcome to tute dude" to the end of the file.

Finally, it opens the file in read mode and prints all of its contents.

Additional Info:
The file1.write(...) call returns the number of characters written, which is printed.

At the end, the entire updated content of the file is displayed using read().

What it teaches:
Writing to a file ("w")

Appending new content to an existing file ("a")

Reading the entire content of a file ("r")

Understanding what write() returns (number of characters written)
