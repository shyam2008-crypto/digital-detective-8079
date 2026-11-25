
# Mission 0 — Create your GitHub workspace

# 1. Task / objective
The goal of this mission was to set up my workspace for the whole assignment: a public GitHub repository with the right name, plus a folder for every mission.

# 2. Work completed
I made a local project folder called `digital-detective-8079` and used the same name for the GitHub repo. Inside it I created a folder and a README.md for each mission (00 to 08), an `evidence/` folder, `number_converter.py` for Mission 5, and a root README.md. After that I connected the folder to GitHub and pushed everything.

# 3. Commands / tools used
- `python3 --version` and `git --version`: to check both tools are installed. I have Python 3.14.7 and Git 2.54.0 (Apple Git-157) .
- `mkdir`: to create the mission folders.
- `touch`: to create the empty README files.
- `git init`: to turn the folder into a Git repository.
- `git remote add origin`: to link my local folder to the GitHub repo.
- `git add`, `git commit`, `git push`: to save my work and upload it to GitHub.

# 4. My understanding
A repository is a folder that Git keeps track of, so it stores my files along with the history of every change I make. I split the work into one folder per mission so everything stays organised, is easy to review, and each mission can get its own commit.

cat >> mission-00-setup/README.md << 'EOF'
# 5. Difficulties faced
- I typed the GitHub repository name wrongly in the first remote URL (the digits were swapped), so Git said "Repository not found".
- I ran `git remote add origin` again, and Git said "remote origin already exists".
- I tried to push before making my first commit, and Git said "src refspec main does not match any".

# 6. How I resolved them
- I checked the exact repository name on GitHub and used the correct one.
- I learned that the remote was already added, so I did not need to add it again.
- I ran `git add .` and `git commit` first so that there was something to push, and then the push worked.

# 7. Evidence / files
- `mission-00-setup/README.md`
- Root `README.md`
- The mission folders and the `evidence/` folder in the repo

# 8. Commit details
- Commit message: Set up Digital Detective mission structure
- Pushed to GitHub: Yes, and I checked the repo page to confirm the folders and the commit were there.