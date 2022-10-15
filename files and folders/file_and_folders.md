# Create

- Files
New-Item new_file_name
- Folders
mkdir folder <br>
New-Item folder_name -Type Directory

# Remove

- File
Remove-Item file
- Folders
Remove-Item -path '.\folder'
Remove-Item folder -recurse

# Rename

- Files
Rename-Item old_file_name new_file_name
- Folders
Rename-Item test_folder test_folder2

# Move

-Files
Move-Item file_name folder1\folder2\new_file_name
- Folders
Move-Item test_file '.\some new folder\new_file_name'
