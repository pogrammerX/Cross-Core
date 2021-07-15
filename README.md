# NEW things in CrossCore
(NEW) File Management(C#: System.IO)

# About CrossCore
CrossCore is an script programming language for Windows maybe i add MacOS/Linux support in the Future!

# Developers
[David Gerson](https://github.com/pogrammerX)

# ---Documentation---
# How to Download CrossCore

1. Download CrossCore
2. Put The files Somewhere(They need to be in the same directory)
3. Copy The Path where you put CrossCore.exe
4. Create an .cco file
5. Open It
6. Check the checkbox
7. Click on More Apps
8. Click on search App
9. Goto the path from the exe
10. Select the exe
11. You have now successfully setuped CrossCore

# How to use CrossCore

In your .cco file you can run these commands:

print (Message/Variable) - Prints an message in the Console

wfile <Path> - Writes an file With the value of the NextIOWrite variable
  
rfile <Path> - Reads an File and puts the file content the the LastIORead Varible
  
cfile <Path> - Creates an file with no content
  
afile <Path> - Applys the value of NextIOWrite to the file
  
dfile <Path> - Deletes an file

title (Title) - Sets the console Title
  
::WaitForUserKeyPress - Waits until the user presses a key(WARNING: Always put this at the end of your script!)
  
Varibles:

---IO---
Varaible: NextIOWrite - The text of the next file to write (This variable is always Created no need for $NextIOWrite)
Varaible: LastIORead - The text of the last file read (This variable is always Created no need for $LastIORead)
---IO---
  
$(VarName) - Creates an variable
  
_(VarName) (Value) - Sets an variable value
