1. Shell Script to Print System Information -> (a)Create a file named system_info.sh:
![image](https://github.com/user-attachments/assets/c15de3f0-56f0-45a2-ba5c-95678d59f3fa)

(b)Make the script executable: chmod +x system_info.sh

(c)Run the script: ./system_info.sh
![image](https://github.com/user-attachments/assets/64fa4db9-dc7d-48d6-827a-307898489b0e)

2.Shell Script to Perform Basic Mathematical Calculation -> (a)Create a file named calc.sh:
![image](https://github.com/user-attachments/assets/b4ffdcbc-0230-41b8-bb3e-12b58ff99cf0)

(b)Make the script executable: chmod +x calc.sh

(c)Run the script: ./calc.sh
![image](https://github.com/user-attachments/assets/b3bf86d6-61e8-43cd-927f-7e860cda95c0)

3.Use Redirection Operators to Store Output of Commands -> (a)Redirect stdout to a file: ls > output.txt
![image](https://github.com/user-attachments/assets/f14dced0-3ab1-4ea6-a4ef-da9984cf051c)

(b)Append output to an existing file: date >> output.txt
![image](https://github.com/user-attachments/assets/3264cb6d-5536-4192-bd92-bf5b6a85b737)

(c)Redirect stderr to a file: ls nonexistentfile 2> error.txt
![image](https://github.com/user-attachments/assets/6205d46f-0976-49ef-bd3f-197c4da62a5e)

(d)Redirect both stdout and stderr to a file: ls . nonexistentfile &> all_output.txt
![image](https://github.com/user-attachments/assets/1696e8b2-a7a6-4423-8fe3-a912e030f4d7)

(e)Pipe output to another command: cat file.txt | grep "keyword"

![image](https://github.com/user-attachments/assets/df02f17d-9d17-401d-947c-3a6aef77db86)

