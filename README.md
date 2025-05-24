The first step in password cracking using John the Ripper is to make sure it’s installed on your chosen Linux distribution. In this lab, we’re using Kali Linux.

![installing John](https://github.com/user-attachments/assets/fc9031a0-70b5-403d-aeff-26ca188ffa12)

Next, generate a SHA-512 password hash for the password letmein using the openssl passwd command.

![Create letmein](https://github.com/user-attachments/assets/18499fa7-49af-44d4-993f-adb9ecccee7b)

Finally, run the John the Ripper command to begin cracking the password. The length of time it takes to crack a password depends on the complexity of the characters.
For example implementing characters such as a # or ! may make the process longer.

![Cracking Password](https://github.com/user-attachments/assets/e22a9027-4eeb-4bf4-9477-6d35e7c84977)


