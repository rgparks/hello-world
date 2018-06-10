Github doesn't really think about folders.  All folders must contain a file.
If you want to put a file into a folder. You type in the name of the folder followed by a "/" forward slash and then the name of the file.
If you want to move the file up a folder you start by typing "../".  This will move the file up a folder.
Not having a file in a folder is sometimes a problem because for example a /build folder may be needed otherwise you will not be able to use the project.
To get around this a common pattern has emerged to create an empty file named .gitkeep in any folder taht you need to create but does not need to have any files.
