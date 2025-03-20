1.Create the /home/consultants directory: -> sudo mkdir /home/consultants
![image](https://github.com/user-attachments/assets/eac00277-b8b8-4f31-a923-37ba6cad4655)

2.Add write permission to the consultants group (symbolic method): -> sudo chmod g+w /home/consultants
![image](https://github.com/user-attachments/assets/231fe8a0-a982-4796-b1ce-e96128fb37c6)

3.Forbid others from accessing the /home/consultants directory (octal method): -> sudo chmod 750 /home/consultants
![image](https://github.com/user-attachments/assets/8f548682-3bbb-4682-a527-1c893b37c829)
![image](https://github.com/user-attachments/assets/bc4f16ba-c37b-4293-8e4f-6871299247e8)

4.Change the default umask for the operator1 user: -> 
(a)Open the user’s .bashrc or .profile file: sudo nano /home/darksoul/.bashrc
(b)Add the following line to set the umask: umask 0074
![image](https://github.com/user-attachments/assets/ea0e602d-6c07-4add-97ef-89a05ff612b7)
![image](https://github.com/user-attachments/assets/79231daf-427a-48fd-a2cc-5e89e340169f)
![image](https://github.com/user-attachments/assets/bc6b1f72-384a-4abd-bf23-53f09d1db606)
5.Confirm the umask: -> su - ubuntu umask
![image](https://github.com/user-attachments/assets/f69457bd-cfda-4415-a26a-5018d266e90f)




