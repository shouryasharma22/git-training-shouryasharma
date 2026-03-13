Commands-

git start ignore-them
(I made a .gitignore file to add those files which i want to ignore)
nano .gitignore
(I manually added these files into gitignore after using nano-
    *.o 
    *.exe
    *.jar 
    libraries/
)
git add .gitignore
git commit -m "Ignored the given types of files"