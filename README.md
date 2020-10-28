# Automatic File Manager
This is a program that sorts the files in your folder into separate folders of pdf files, text files, images etc.

What the project does:
Given the full location of the folder containing the files to be sorted, it creates four separate folders named 'images', 'pdf_files', 'text_files' and 'miscs' and puts these
files in their respective folders automatically.

Necessary requirements:
Python 3

Steps to set up:
1) Create a folder (ex. 'proj1')
2) Inside this folder proj1, create another folder named 'file_manage'
3) Inside the file_manage folder, put the 2 source code files given above. 
4) Create an empty text file named 'output' and save it in the file_manage folder.
Note- file_manage and output names are to be entered as they are without any change in name or case
5) Store all the files to be sorted outside the file_manage folder but inside the proj1 folder.
6) Open the GUI_file in python IDLE and run the program
This will launch the application
7) Copy the full path of the proj1 folder and paste it in the tkinter GUI window and then click on confirm and manage buttons.
This will create extra folders and sort the files and also write into the output.txt files the names of the files that were moved.
This will also create a path.txt file automatically tha stores tha path of the sorted folder.
