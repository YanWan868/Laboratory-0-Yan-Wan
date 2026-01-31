# Laboratory-0-Yan-Wan

## Repositories
<img width="1481" height="376" alt="image" src="https://github.com/user-attachments/assets/b1f2baad-0358-40c6-8339-856bbe57613d" />
To build a project, you should create a new repository to store our code , images, notes and documents. It’s kind of like a folder stored in the cloud, you can also think of it as a “remote repository”. As long as you allow it, anyone can view and download the stuff stored there. At the same time, it keeps a revision history of every document, so you can check it at any time.

## Git bash
Firstly, I download the gitbash and register it with my name and email.
<img width="714" height="243" alt="image" src="https://github.com/user-attachments/assets/6a2258d2-9b1f-46b4-9803-67e77ce9ba48" />

## Cloning
Secondly, after registering it, if you want to clone a repo in github. Open the folder where you want to download the repository. Copy the HTTPS link from GitHub, then use:
```bash
git clone
```
to clone it.

<img width="814" height="301" alt="image" src="https://github.com/user-attachments/assets/32ad7802-d980-4564-b7e3-0ae224980a0b" />
The result shown in below. You can find it in the folder you choose.
<img width="1511" height="1170" alt="image" src="https://github.com/user-attachments/assets/b952082f-c9a7-4657-b8e0-b29aef898546" />

## Check the status
Shown in below, I entered the repository directory using:
```bash
cd ~/lab0-YanWan868 and verified that .git/
```
and README.md were present by running:
```bash
ls -a
```
Then I checked the repository status with:
```bash
git status
```
which showed that the current branch is main, and the working tree is clean. Finally, I use:
```bash
git log --oneline
```
to view the commit history and found two commits: c62916d add deadline and e512838 Initial commit.

<img width="705" height="414" alt="image" src="https://github.com/user-attachments/assets/cff0bee6-5858-4c3a-a07d-ba146814d86a" />

## Other commands
Also, there are some other commands, just like: git diff helps me quickly check exactly what lines I changed before submitting anything. Then I could use git add to stage the files I want to include, and git commit -m to save those staged changes as a new version with a short message. Finally, git push uploads my local commits to GitHub so the remote repository reflects my latest work.

## Conclusion 
Honestly, it's not my first time to use github, but it's my first time to explore in github! (*^▽^*) It's really a perfect platform that allows anyone to share any interesting ideas. I hope that in the future I can also do some meaningful work here and share my own ideas on it.


