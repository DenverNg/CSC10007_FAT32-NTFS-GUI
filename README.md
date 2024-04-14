# FAT32_NTFS_GUI

- This is Project 02 in my Operating System Class - HCMUS. Program is written by Python (ver 3.11.4) and Tkinter library for UI. 
-  This project was required to be done in a team of 1-2 people, but due to a few reasons, I ended up doing this repo alone. 
- The project lasted for 3 weeks, and I managed to complete this repo within 5 days (due to a very annoying bug in C#, I switched to Python just 5 days before the deadline.
)
### 1. Requirements
Assuming a memory card or USB is divided in to at least 2 partitions, in which: 
- One partition is formatted in FAT32 format.  
- One partition is formatted in NTFS format.<br>
  
Our task is creating a program have a graphical user interface (GUI) and the following functions:
1. Automatically detect the format of each partition (FAT32 / NTFS). 
2. Display the directory tree of each partition when selected. 
3. The display name of the folder/file on the directory tree is the full name (Long File Name). 
4. The folder can be collapsed/expanded by user interaction. 
5. When selecting any folder/file, read and display information for the user, including:  
   - Name (including extension if any) 
   - Attributes 
   - Date created 
   - Time created 
   - Total Size <br>
  
### 2. Bonus Point (but I can't afford to do it lol) 
If the group implements additional functions have these functions:
- Delete and Restore folder/files
- Displaying the content of the selected file (text format only)
- Any other relevant functionalities
### 3. How to run
- You have to install some library to display full features (such as PIL, tkinter,...)<br>
- Remember to run your IDE as **administrator** before run this program by:
`py interface.py`

### Note:
If you're looking to rely on this repo for your school assignments (specifically HCMUS), here are some errors and deficiencies that I've found but didn't have enough time to fix (partly due to my laziness as the deadline has passed and I don't want to update this repo to perfection):

- Of course, the bonus part is the most regrettable; if you're using this repo, try to complete the bonus section.
- Some features I could mention if you're interested (can use APIs without coding): adding files, renaming, opening PNG files, previewing PDF files, etc.
- The UI is still simple; the blocks in the UI are still stuck together, somewhat lacking in aesthetics.
- The information section of FAT32 and NTFS could display more complete information, but due to the rush of the project, I overlooked it.
