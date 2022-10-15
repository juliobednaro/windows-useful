# Create folder

mkdir folder <br>
New-Item folder_name -Type Directory

# Remove folder

Remove-Item -path '.\folder'
Remove-Item folder -recurse

# Rename folder

Rename-Item test_folder test_folder2

# Create file

New-Item file <br>
New-Item -Path "C:\Hello\World\script.js"

# Rename file

Rename-Item file new_file_name

# Remove file

Remove-Item file <br>
Remove-Item *
