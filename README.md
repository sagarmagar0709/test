"# test" 
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sagarmagar0709/test.git
git push -u origin main

Check the status:
bash
Copy
Edit
git status
Add changes:
bash
Copy
Edit
git add .
Commit changes:
bash
Copy
Edit
git commit -m "Your commit message"
Step 6: Push to GitHub
If it's a new repo, set the remote:
bash
Copy
Edit
git remote add origin https://github.com/your-username/your-repo.git
