**Instruction**:
 This is the course work of System Security.

 The program is about recovering some passwords from a set of `hashes`. 
You are provided with a file containing one hash value per line, and you should output a new
file, where each line contains the hash value, followed by the original password if found.

 The program takes as input the name of the text file containing the set of hashes and the
name of the file where the output should be written. It should complain if the hashes files
does not exist, and erase the previous output file if it exists. 
 
**Password Principles**:
 The file `hashes.txt` contains 8 hashes in the file, which corresponded to eight passwords hashed with SHA-256. The passwords are
defined as follows:
 1. A simple, lower-case, first name (e.g., alice), among the 20 most popular girl names in
England.
 2. Or, a simple, lower-case, first name (e.g., bob), among the 20 most popular boy names
in England;
 3. Or, a name, as specified in the dictionaries of 1 and 2, but with no specified case and
with a number up to 9999 at the end (e.g., BoB17, aLICe1920);
 4. Or, a lower-case English word;
 5. Or, a combination of 4 alphanumerical characters, with no specified case, and with
special characters “_!@#$%^&*” (e.g. !tZP, Y@6a).



**Instructions**:
 A.	Run Class Dic3Generate
Run main method in Class Dic3Generate, file "names.txt" which concludes dictionary 1 and 2 is required.
 B.	Run Class Dic5Generate
Run main method in Class Dic5Generate.
 C.	Run Class Recover
Run main method in Class Recover. You need input the correct hashes and output file paths.
