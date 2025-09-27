# Exercise 6: Copy and Rename Files
#### Name : Gayathri M
#### Register Number : 212223220024

# Aim:
To copy a file (or folder) from a source location to a destination location with a new name using UiPath.

# Procedure:


1. For Copying a File and Renaming

Drag and drop the Copy File activity.

In Path (Source), give the full path of the file to copy.
Example: "C:\Users\Admin\Documents\Report.xlsx"

In Destination, give the target path with the new name.
Example: "C:\Users\Admin\Documents\Report_Backup.xlsx"
 Here, the file is not only copied but also renamed.

2. For Copying and Renaming a Folder

Use Copy Folder activity (UiPath.System.Activities package).

In Path, give the source folder path.

In Destination, give the new folder path with the renamed name.
Example:

Source: "C:\Projects\OldFolder"

Destination: "C:\Projects\NewFolder"

3. Alternative Using Assign (If no activity is used)

If you want to rename after copy:

Use Copy File activity to copy with the same name.

Then use Move File activity to rename the copied file to the new name.

# OUTPUT :

<img width="1920" height="1080" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/46480ed0-060a-456a-9655-0a85b1b20e54" />

<img width="1920" height="1080" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/ec8ffaec-879f-4507-9768-324bd9294f4c" />

<img width="1920" height="1080" alt="Screenshot (66)" src="https://github.com/user-attachments/assets/2d63ff6d-e0ad-4468-b61e-c2ce3c7b4b59" />






# Result:
The file/folder is successfully copied to the destination path with the new name.
