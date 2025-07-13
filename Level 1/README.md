Bandit Level 0 → Level 1

Level Goal
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

Commands you may need to solve this level
ls , cd , cat , file , du , find

TIP: Create a file for notes and passwords on your local machine!

Passwords for levels are not saved automatically. If you do not save them yourself, you will need to start over from bandit0.

Passwords also occasionally change. It is recommended to take notes on how to solve each challenge. As levels get more challenging, detailed notes are useful to return to where you left off, reference for later problems, or help others after you’ve completed the challenge.


Solution: 

I created a new secure shell file, gave it run permission using chmod. Once inside the bandit0 machine, I used ls to view all the files on the home directory. The readme file wasthe only file in the directory. All I had to do was use the concatenate command to retrieve the password.

<img width="1374" height="1304" alt="level0-1" src="https://github.com/user-attachments/assets/adc132bf-9460-4ffd-b556-f66d54380d56" />


<img width="1374" height="1304" alt="level-1" src="https://github.com/user-attachments/assets/8433cbbd-fcdd-4a47-a3ba-178a1fda9483" />
