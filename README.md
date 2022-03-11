# Terminal

# Navigating around

option + left arrow / right arrow → jump front and back among the words <br>
control + a → goes to the beginning of the line <br>
control + e → goes to the end of the line <br>
cd - → similar to the back button <br>
cd . → current directory <br>
cd .. → goes back one directory <br>
cd example\ folder → access folder example folder (contains space, necessary \ to scape) <br>

# Tricks
control + u → erases the entire line <br>
control + k → erases from the cursor to the end <br>

# Listing files
ls → list files <br>
l → more information <br>
a → all (including hidden files) <br>
h → human, show sizes of files in a more understandable way (Kb, Mb, Gb) <br>
R → recursive, show the three of files underneath the current folder <br>
S → order by size, bigger files first <br>

# Interacting with files
file → shows info about the file, its type, resolution (if its the case), etc… <br>
stat → show files owner, when it was created, when it was modified, size, etc… <br>
touch → creates a file or change its date of creation (if already exists). It works on folders as well <br>
cp -r folder container → Use -r to copy a folder and its content inside to another folder <br>
mv → move or copy files or folder. E.g.:e mv file_or_folder_to_be_moved destination <br>
rm → remove file <br>
find . -type f -name "*.txt" → Find all .txt files extension in the current directory (iname for case-insensitive) <br>
less → Used to read the content of a file, shows the initial part (pagination with cursos arrows) <br>
cat → Used to read the content of a file, shows the entire content (scrow may be necessary)

# Interacting with folders
mkdir -p test/folder1 test/folder2 → Creates a folder called test and inside of it two others called folder1 and folder2 <br>
mkdir -p test1 test2 → Creates two folders, test1 and test2 <br>
rm -r → Remove folders and whatever is inside it <br>
rm -rf → Removes with force argument, without asking or considering permissions <br>
find . -type d -name "\*site\*" → Find folders with site in its name in the current directory (iname for case-insensitive)

# Wildcards

\* → used to replace one or more characters. E.g.: rm file* to remove everything that starts with file <br>
? → used to replace one character. E.g.: rm file* to remove everything like file1, file2 but not file22, file231 <br>