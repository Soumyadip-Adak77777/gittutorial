New git setup
==============
1. create project folder on local system.

2. in that folder open git bash and enter git init

3. create a Readme.md file under that folder and save.

4. create a repository in github

5. git add Readme.md

6. git commit -m "first commit"

7. git branch -M main 

8. git remote add origin https://github.com/Soumyadip-Adak77777/gittutorial.git

9. git push -u origin main  **

** if you get any error for authentication or shell access then
** create ssh key for git authentication and set it for authentication

10. 
**Recommended: Ed25519 - Because Why Not Go for Gold?
ssh-keygen -t ed25519 -C "soumyadipadak@gmail.com"
**Alternative: RSA — The Classic
ssh-keygen -t rsa -b 4096 -C "soumyadipadak@gmail.com"
**For the Paranoia Pros: Extra Secure RSA
ssh-keygen -t rsa -b 8192 -C "soumyadipadak@gmail.com"

11. go to C:\Users\UserName\.ssh and open id_ed25519.pub in notepad and copy the body.

12. paste it in (click in profile pic in github-> in dropdown select Settings -> click on SSH and GPG keys -> New SSH key )-> Add SSH key

13. test the connection by ssh -T git@github.com and you see the message of success or failure.

14. after success hit git remote set-url origin git@github.com:Soumyadip-Adak77777/gittutorial.git

15. git push -u origin main and check it in github.




