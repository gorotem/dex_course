# dex_course
Linux Day1 - homework rotem

## Part 1: VirtualBox & Ubuntu Installation

``VirtualBox & Ubuntu`` affter download and installation:

![image](https://github.com/user-attachments/assets/b76ac24d-37f7-43cd-a60d-66c1eb62d385)


``cat /etc/os-release``: This command open the "/etc/os-release" file and display its contents.

![image](https://github.com/user-attachments/assets/722285b1-1ecb-4cbf-9bfd-abcf4a4e08a1)


## **Part 2: Linux Directory and File Creation**

**1.**	Create Directories and Files:

○	Create a directory structure:
~/homework/{dir1,dir2,dir3}.

![image](https://github.com/user-attachments/assets/5e807e95-d474-436f-bb00-ad720616b42f)


○	Inside dir1, create a few text files:
~/homework/dir1/{file1.txt,file2.txt,file3.txt}.

![image](https://github.com/user-attachments/assets/a558885f-c324-4a8a-b740-29289bd7e242)


**2.**	Add Content to Files:

○	Use echo to add text to files, e.g.,
~/homework/dir1/file1.txt.

![image](https://github.com/user-attachments/assets/29e54cab-0543-4d0d-b3e7-37526e06dc8f)



## **Part 3: Using grep and find Commands**

**1.**	grep Command:

○	Search for text within files using grep. Example:
~/homework/dir1/*.txt.

![image](https://github.com/user-attachments/assets/56c36347-1783-4e9e-a149-1c24c11efe33)

**2.**	find Command:

○	Find files in a directory.

``find . -type -f``: this commant will serarch for file type only, in current directory.

![image](https://github.com/user-attachments/assets/ef15a6cb-1ec4-4428-ab8d-fccb823d491d)


○	Find files modified within the last 7 days.

``find . -type f -mtime -7``: This command will search for files in the current directory and its subdirectories that have been modified within the last 7 days.

![image](https://github.com/user-attachments/assets/08396cae-4663-468e-852e-5b01e5549ac3)
