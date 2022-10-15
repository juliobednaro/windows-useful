# Create

- Files <br>
New-Item new_file_name
- Folders <br>
mkdir folder <br>
New-Item folder_name -Type Directory

# Remove

- Files <br>
rm file
Remove-Item file
- Folders <br>
rmdir folder
Remove-Item -path '.\folder' <br>
Remove-Item folder -recurse

# Rename

- Files <br>
Rename-Item old_file_name new_file_name
- Folders <br>
Rename-Item test_folder test_folder2

# Move

- Files <br>
Move-Item file_name folder1\folder2\new_file_name
Move-Item file* folder\temp\
- Folders <br>
Move-Item test_file '.\some new folder\new_file_name'
