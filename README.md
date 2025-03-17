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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .header {
            background: #007bff;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .nav {
            display: flex;
            justify-content: center;
            background: #0056b3;
            padding: 10px;
        }
        .nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        .hero {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 50vh;
            background: #f4f4f4;
            text-align: center;
        }
        .footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Welcome to My Website</h1>
    </div>
    <div class="nav">
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </div>
    