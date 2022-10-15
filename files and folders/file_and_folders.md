# Create

- Files
New-Item new_file_name
- Folders
mkdir folder <br>
New-Item folder_name -Type Directory

# Remove

- File <br>
Remove-Item file
- Folders <br>
Remove-Item -path '.\folder'
Remove-Item folder -recurse

# Rename

- Files <br>
Rename-Item old_file_name new_file_name
- Folders <br>
Rename-Item test_folder test_folder2

# Move

-Files <br>
Move-Item file_name folder1\folder2\new_file_name
- Folders <br>
Move-Item test_file '.\some new folder\new_file_name'
