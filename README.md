# Python-Import-and-Use-a-Module
Import the os module.

Place your insertion point on line 4, and press Enter.

Type import os and press Enter.

Verify that PyCharm has turned the text grey.

This is because, at the moment, you haven't used this module in your code.

Test out the module by calling one of its methods.

Place the insertion point at the end of line 104, and press Enter.

Type the following code, including the empty line at the end.

Line 106 references the expanduser() method from the os.path module, which extends the os parent module. The expanduser() method uses ~ to return a string value of the current user's home directory. This prevents you from needing to reference the path directly, and it can also work on Linux and Mac OS X environments. The rest of the argument adds the user's desktop to the directory path. The print statement in line 107 is temporary for testing purposes.

Verify that Python has referenced your desktop correctly.

Run the program.

Type in any test values as input, but say yes to outputting the results to a file.

Verify that Python printed the correct path to your desktop directory.

Note: By default, Windows uses backslashes in directory names, and Python follows this convention. However, Windows can also handle forward slashes, which is why this mix of both slash types is acceptable.
