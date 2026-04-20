### GitHub Workflow (Using git clone)
# Simple Workflow You Need
You only need these 3 Git commands after cloning:

# Step 1: Clone Repository (done once)
git clone <repo-url>
# Downloads project from GitHub ? Automatically connects GitHub repo

# Step 2: Go into Folder
cd your-folder-name
Example:
cd C:\CBC\DSAI\04-NOSQL\MyNotes\test-mongodb\Mongodb-cmd


# Step 3: Add Changes
git add .

#Stages all changes (new + modified files)

# Step 4: Commit Changes
git commit -m "your message"
Example:
git commit -m "My mongo cmd first File to add"

# Saves a snapshot of your work

# Step 5: Push to GitHub
git push

#Sends changes to GitHub

#FINAL SIMPLE FLOW (ONLY THESE 3 COMMANDS)
After cloning, you only use:
git add .
git commit -m "message"
git push

# Memory Trick
* clone = get project once
* add = select changes
* commit = save snapshot
* push = upload to GitHub

mini cheat sheet:
------------------------------  
git clone <repo-url>
cd folder-name
git add .
git commit -m "message"
git push
---------------------------------
