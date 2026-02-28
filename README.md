Description

The script automatically sorts files in the specified folder by type:

.txt → txtFiles

.jpg → jpgFiles

.pdf → pdfFiles

.bmp → bmpFiles

Other files → otherFiles

The script also outputs:

number of files of each type

the largest file

total size of all files in the folder (MB)

How to use

Clone the repository or download the script.

Install Python 3.x if it's not already installed.

Place the script in the folder you want to organize.

Run the script:

python file_organizer.py

After execution, folders txtFiles, jpgFiles, pdfFiles, bmpFiles, otherFiles with sorted files will appear.

Features

Uses the pathlib module to work with paths.

Uses the shutil module to copy files.

Works with extensions case-insensitively (for example, .JPG and .jpg are recognized the same).

Does not delete original files (only copies).

Possible improvements

Add the ability to recursively traverse subdirectories.

Option to delete original files after copying.

Sorting by da
