1.ps Command -> (a)Display all running processes: ps aux
![image](https://github.com/user-attachments/assets/17281e58-e101-48fc-a404-91f7efaf09be)
(b)Show processes for the current terminal session: ps
![image](https://github.com/user-attachments/assets/76c487ae-72b7-42e1-823e-02d7a8b1f94d)

(c)Display a process tree: ps -e --forest
![image](https://github.com/user-attachments/assets/68188369-5cef-4324-ba39-b4b8f33558b7)

(d)Filter by process name: ps -C firefox
![image](https://github.com/user-attachments/assets/c9b5fbc4-acbb-475f-934d-d3407220eeeb)

(f)Show detailed information of a specific process: ps -p 1234 -o pid,ppid,cmd,%mem,%cpu
![image](https://github.com/user-attachments/assets/1f6d4d1e-e4d5-467e-8eb3-95146d189544)

2.kill Command -> (a)Find the PID: ps aux | grep firefox
![image](https://github.com/user-attachments/assets/dea32289-8170-44d5-b5ab-b16e5d1abe7a)

(b)Kill a process by PID: kill 1234

(c)Force kill a process: kill -9 1234

(d)Kill by process name: killall firefox

3.apt-get Command -> (a)Update package list: sudo apt-get update
![image](https://github.com/user-attachments/assets/58c7750c-98e9-40e2-ab04-203e4f118f79)

(b)Upgrade installed packages: sudo apt-get upgrade
![image](https://github.com/user-attachments/assets/30fcdaf9-02af-4db5-8db0-d61b19bc243a)

(c)Install a package: sudo apt-get install vim
![image](https://github.com/user-attachments/assets/fe477715-28eb-4079-ab6e-96f08cc45e0a)

(d)Remove a package: sudo apt-get remove vim
![image](https://github.com/user-attachments/assets/e89c7680-5064-476b-b349-b7879adc8ed7)

(e)Remove package along with configuration files: sudo apt-get purge vim
![image](https://github.com/user-attachments/assets/7c6b65eb-683f-421e-b8f3-2bd91f91d47a)

(f)Clean up unused packages: sudo apt-get autoremove
![image](https://github.com/user-attachments/assets/34597b4d-b623-43d3-8c6d-89096c839212)

(g)Clean package cache: sudo apt-get clean
![image](https://github.com/user-attachments/assets/28b4d42e-e907-49d7-a3d2-20366811c40e)
