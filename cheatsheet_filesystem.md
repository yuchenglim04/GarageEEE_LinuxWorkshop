```
# is for comment. Don't copy anything after the #
<> means variable. Replace with the name/string/number that you want
```


```
pwd                        # path fo working directory/where are you?

cd                          # go home
cd ~                        # go home
cd /                        # go root
cd <folder name>            # change directory to folder
cd ..                       # go one level up/exit the folder
cd *asd                      # for long names, just use *
cd *asd*                 (says "too many arguments" if multiple found)
cd ../*lab*
                               
ls                              # list of files/folders
ls -a                           # list all, including hidden files
ls -af                          # list all, with additional info
ls | grep name                     #search
ls | grep 'name'                     #search

mkdir <name>                       # make directory/create folder
rmdir <name>                       # remove empty directory

cp <original> <new_name>            # copies into same folder, new name specified
cp <original> <directory>          # copies into different folder, same name as original
cp <f1> <f2> <f3> <directory>      # copies multiple files into different folder, same name as original
cp <original> <path/new_name>      # copies into different folder, new name specified
cp -t <target_directory> <original> # copies into "target" folder, same name as original

mv <old name> <new name>             # rename
mv <file> <destination>              # move the differen folder

rm <f1> <f2>                        # remove multiple files at once
rm -i <f1>                         # prompts before removal
rm -r <directory>                  # remove non-empty directories
rm -rf <directory>                 # remove non-empty directories with protected files

vi filename                        # create a text file


cat filename                      # print out whole file in terminal
head filename                      # print out first few lines
tail filename                      # print out last few lines
tail -5 filename                    # print out last 5 lines
more filename                      # includes some user interface
less filename                      # includes some user interface

chmod -c ug+wx <filename>                                  #u g o a   + - =   r w x

```



advanced
```
top                      # like programme manager
df                      # 
df -h                    
gcc filename            # compile your C file hahahaha
```
