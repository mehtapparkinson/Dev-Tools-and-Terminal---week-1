# Dev-Tools-and-Terminal---week-1
Assignment - week 1

(To see where you are)
OCC-C012s-MacBook-Air:documents occ-c012$ pwd
/Users/occ-c012/documents

Make a directory named first
OCC-C012s-MacBook-Air:documents occ-c012$ mkdir first

Go in the file named first
OCC-C012s-MacBook-Air:documents occ-c012$ cd first

See where you are:
OCC-C012s-MacBook-Air:first occ-c012$ pwd
/Users/occ-c012/documents/first

Create file:
OCC-C012s-MacBook-Air:first occ-c012$ touch person.txt

Rename it:
OCC-C012s-MacBook-Air:first occ-c012$ mv person.txt another.txt

Make a copy of a file:
OCC-C012s-MacBook-Air:first occ-c012$ cp another.txt copy.txt

Remove the file:
OCC-C012s-MacBook-Air:first occ-c012$ rm- r copy.txt
-bash: rm-: command not found
OCC-C012s-MacBook-Air:first occ-c012$ rm -r copy.txt

To see where am I:
OCC-C012s-MacBook-Air:first occ-c012$ pwd
/Users/occ-c012/documents/first

To go back once:
OCC-C012s-MacBook-Air:first occ-c012$ cd ..

To copy folder:
OCC-C012s-MacBook-Air:documents occ-c012$ cp first second
cp: first is a directory (not copied).
(Did not work because it had content in it)

Make copy of a folder with content:
OCC-C012s-MacBook-Air:documents occ-c012$ cp -r first second

Remove the directory with content:
OCC-C012s-MacBook-Air:documents occ-c012$ rm -r second


