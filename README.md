Hide files in an image.
Extract files from that image.

You will need 5 files:
7z.exe								- not optional. File needed for archive.
AutoIt3.zip							- optional. You can change the filename or you can use 7z, rar as archive or other but not tested.
metaphysical-animal.jpg				- optional. You can change the filename or you can use a png image or other but not tested.
Hide file in a piture.bat			- script needed to hide files in a picture.
extract files from a picture.bat 	- script needed to extract files from a picture (not any picture, just the one you created w the script above).

<==Hide files in an image.==>
Create a batch file with the command-line: copy /b "metaphysical-animal.jpg" + "AutoIt3.zip" "Test.png"
Name it "Hide file in a picture.bat", save it and run it.

<==Extract files from that image.==>
Command-line: 7z.exe e Test.png
If you want to extract it in another folder, use -o%TEMP% at the end. Ex.: 7z.exe e Test.png -o%TEMP%.
Filename: extract files from a picture.bat
Save it and run it.
