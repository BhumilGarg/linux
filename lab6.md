1. Create the operator1 user: -> sudo useradd -m operator1
![image](https://github.com/user-attachments/assets/797952bf-e3c0-4a03-99df-88a39e025260)

2. Confirm that operator1 exists: -> cat /etc/passwd | grep operator1
![image](https://github.com/user-attachments/assets/8efce82a-6b20-4e41-b0ea-aafb329dd79c)

3.Set the password for operator1: -> sudo passwd operator1
![image](https://github.com/user-attachments/assets/85dc346d-a694-4896-8f94-0f0225e514db)

4.Create operator3 and operator4 users: -> sudo useradd -m operator2 sudo passwd operator3 sudo useradd -m operator4 sudo passwd operator3
![image](https://github.com/user-attachments/assets/f135a6a9-3dbc-4c0c-9044-d8d8e7259d09)

5.Update the comment for operator1 using usermod -c: -> sudo usermod -c "System Operator 1" operator1
![image](https://github.com/user-attachments/assets/f013396a-a8aa-4548-ab10-106acc6dbb75)

6.Remove the operator3 user: -> (a)To delete operator4 without removing the home directory: sudo userdel operator4
![image](https://github.com/user-attachments/assets/d2ddd6a6-c37a-4baf-80c3-400c160173cb)

(b)To delete operator3 and its home directory: sudo userdel -r operator4
![image](https://github.com/user-attachments/assets/b692105b-2dfb-43fd-9b56-75d67b1316cd)

