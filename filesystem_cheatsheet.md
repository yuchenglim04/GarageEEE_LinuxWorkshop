```
cd                       go home
cd ~
cd /
cd <filename>
cd ..
cd *asd*                 (too many arguments if multiple found)
cd *asd
cd ../*lab*

l                               # list all; if file, filename/
ls
ls <file name*>                 # list the said files
ls <folder name*>               # ls all the said files&folders!
ls <dir1> <dir2> <dir3>         # ls multiple directories
ls -d filename                  # listing files, and directories instead of opening them
ls -d folder/                   # only folders
ls -d */                        # list directories only
ls -d */ | wc                   # then count!
ls -a                           # hidden files
ls -F                           # append suffix to files (file types)
ls -m                           # comma separated lists
ls -C                           # output in multiple columns
ls -1                           # 1 column of output
ls -s                           # indicates estimate of file size

ls - mF                         # Ways to combine commands
ls -m -F
ls -F ..                        #go one level up and -F

ls -R                           #listing recursively
ls -l                           #long listing

ls | grep 'name'                     #search

mkdir <name>
rmdir <name>                       #empty directories

cp <original> <path+name copy>
cp <f1> <f2> <f3> <directory>

mv <file> <destination>
mv <old name> <new name>

rm <f1> <f2>
rm -i <f1>                         #prompts before removal
rm -r <directory>                  #remove non-empty directories
rm -rf <directory>                 #remove non-empty directories with protected files

chmod -c ug+wx <filename>                                  #u g o a   + - =   r w x



env
env PATH
env HOME

pwd

df
```
