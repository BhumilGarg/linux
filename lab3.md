1. Open the editing_final_lab.txt file in Vim and Nano:
-> VIM- vim editing_final_lab.txt
   NANO- nano editing_final_lab.txt
  ![image](https://github.com/user-attachments/assets/d1fd5c71-302a-49b9-9904-2b9d75f093d7)
![Screenshot 2025-03-20 133400](https://github.com/user-attachments/assets/4fdb1658-ab92-403c-92ff-aa32bb88741d)

![image](https://github.com/user-attachments/assets/d6d542f4-5074-4c8a-8fea-06b842965e5e)

2. Use the lab_file shell variable:
-> lab_file="editing_final_lab.txt"
   vim $lab_file
   ![image](https://github.com/user-attachments/assets/396bd405-fdaf-4172-b8c0-01eb5c4b1bc9)

 ![image](https://github.com/user-attachments/assets/52604aa0-cf1d-4da8-bc7c-075b51b9e366)
3. Enter visual mode in Vim:
-> Open Vim.
   Press v to enter visual mode.
  ![image](https://github.com/user-attachments/assets/049d206f-72ae-4204-82ef-60f550ffa697)

4. Remove the last seven characters from the first line:-> Press ^ (caret) to go to the beginning of the line.Press v to start selecting characters.Move to the end of the line using $.Press d7 to delete the last 7 characters.

5. Preserve only the first four characters of the first column:-> Go to the beginning of the line using 0.Press v and move to the 4th character using l (right arrow).Press d to delete everything after the 4th character.

6. Save and exit:-> :wq


