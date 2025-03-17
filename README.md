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
2. Restart GitHub Desktop and Browser
Close GitHub Desktop completely.
Restart Google Chrome and log into GitHub.com.
Open GitHub Desktop and try signing in again.
3. Clear Browser Cache
If it still doesn’t work:

Open Google Chrome.
Press Ctrl + Shift + Delete and clear Cookies and Cached Images.
Restart the browser and retry signing in.
4. Check if GitHub Desktop is Blocked
Open Windows Defender or Antivirus settings.
Ensure GitHub Desktop is allowed through the firewall.
Let me know if it's still stuck! 🚀






hello from code


import subprocess

branch_name = "my-new-branch"

# Create and switch to the new branch
subprocess.run(["git", "checkout", "-b", branch_name], check=True)

print(f"Switched to new branch: {branch_name}")
