1. Open the editing_final_lab.txt file in Vim and Nano:
-> VIM- vim editing_final_lab.txt
   NANO- nano editing_final_lab.txt
   ![image](https://github.com/user-attachments/assets/cf0033be-57e3-48fb-9888-eaf039384396)

![image](https://github.com/user-attachments/assets/e212af98-9ae0-45b6-8270-7ab782eba71c)

3. Use the lab_file shell variable:
-> lab_file="editing_final_lab.txt"
   vim $lab_file
   ![image](https://github.com/user-attachments/assets/8565898b-ed2d-4a36-830f-558f850bf807)


5. Enter visual mode in Vim:
-> Open Vim.
   Press v to enter visual mode.
![image](https://github.com/user-attachments/assets/6929187a-e1bd-4da2-93c5-87ebed986260)

6. Remove the last seven characters from the first line:
-> Press ^ (caret) to go to the beginning of the line.
   Press v to start selecting characters.
   Move to the end of the line using $.
   Press d7 to delete the last 7 characters.

7. Preserve only the first four characters of the first column:
-> Go to the beginning of the line using 0.
   Press v and move to the 4th character using l (right arrow).
   Press d to delete everything after the 4th character.

8. Save and exit:
-> :wq


