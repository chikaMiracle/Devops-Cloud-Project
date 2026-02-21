# Devops- Assignment 1
1. Command to create a user: sudo adduser username
   i. Screen shot of all the users I created below:

   <img width="1135" height="648" alt="image" src="https://github.com/user-attachments/assets/ac0c2dbd-d704-4c9a-81a7-4511c4922c2b" />

3. To create a group I used: sudo groupadd groupname, to get list of groups i used getent group
   i. Screenshot of the groups I created: <img width="1147" height="655" alt="image" src="https://github.com/user-attachments/assets/6bbc44fe-4ed5-4dcf-acd8-0a23bc4fb5f7" />

3 To add user to a user I used: sudo usermod -aG groupname user, to get the list of group and users assigned to each group I used: getent groupname
 i. Screenshot of the different groups i added each user: <img width="1202" height="652" alt="image" src="https://github.com/user-attachments/assets/669278be-5d78-4b91-ba8e-0dac128330c7" />

4. To created directory:  mkdir Businss_Models and to assign group to directory sudo chown :groupname directoryname
   i. screenshot of each group and their directory: <img width="1132" height="652" alt="image" src="https://github.com/user-attachments/assets/f925260e-8d1b-4bf4-9dd9-ef50415b0244" />

5. To see list of permissions: ls -l
    1. screenshot of group and directory permissions: <img width="1092" height="618" alt="image" src="https://github.com/user-attachments/assets/5cc40969-95e5-49ed-abcb-c5521c0dd338" />



