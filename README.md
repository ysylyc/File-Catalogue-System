# File-Catalogue-System
Analyze the directory structure on the local machine, looking for duplicate file names and searching for text in specified files.

1. Provide a switch /s which indicates that the entire directory tree rooted at the path is searched for matching files. If the switch is not present on the command line only the directory at that path is searched.
2. Privide a command line option /d which will emit a list of duplicate file names along with their paths.
3. Provide a command line option, /f"search text" which causes the program to list all the files stored in the catalog that contain the search text.
4. If no options are provided on the command line, emit a brief summary, e.g., N Files found in M directories.

