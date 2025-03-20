1.chown Command -> (a)Change the owner of a file: sudo chown operator1 file.txt
![image](https://github.com/user-attachments/assets/ffa062bd-18fa-4210-a75e-a351b7079fd4)

(b)Change the owner and group of a file: sudo chown operator1:group1 file.txt
![image](https://github.com/user-attachments/assets/3cd83bc3-baa9-40c3-b68e-024649f860a3)

(c)Change only the group: sudo chown :group1 file.txt
![image](https://github.com/user-attachments/assets/ff65baf5-e6af-46d4-924d-20ee9b3ac035)

(d)Change ownership recursively (for directories): sudo chown -R user1:usergroup /path/to/directory
![image](https://github.com/user-attachments/assets/796c0824-8b94-463e-9fef-dccbe29db212)

(e)Transfer ownership to root: sudo chown root file.txt
![image](https://github.com/user-attachments/assets/898dc50f-43d6-4df6-a4c2-7fb50a72f382)

(f)Use --from to change from a specific owner: sudo chown --from=current_owner new_owner file.txt
![image](https://github.com/user-attachments/assets/ff203c8c-3753-47c6-b20e-979a38e3b7d2)

2.chmod Command -> (a)Give execute permission to the user: chmod u+x file.txt
![image](https://github.com/user-attachments/assets/887e1756-1f70-43fb-bb4b-e92f829ad5c5)

(b)Remove write permission for others: chmod o-w file.txt
![image](https://github.com/user-attachments/assets/d63ed08d-af96-4c43-be70-49a3f73fc756)

(c)Give read and execute permission to the group: chmod g+rx file.txt
![image](https://github.com/user-attachments/assets/c742c600-44f1-4efe-a8ad-d416175987c0)

(d)Set specific permissions: chmod u=rwx,g=rx,o=r file.txt
![image](https://github.com/user-attachments/assets/01015db4-35c4-4ff0-bddc-0d0c5f06a56a)

(e)Set permissions to rwxr-xr-- using octal mode: chmod 754 file.txt
![image](https://github.com/user-attachments/assets/834e5027-1633-4c61-a7d8-5c1f371290f3)

(f)Recursive Change of Permissions: chmod -R 755 /path/to/directory
![image](https://github.com/user-attachments/assets/84cede74-b49d-4d16-a596-a6e6fe1fcdc7)

(g)Change permissions based on existing files: chmod --reference=ref_file.txt target_file.txt
![image](https://github.com/user-attachments/assets/102fb75f-a755-4102-afc1-57469c5e75aa)
