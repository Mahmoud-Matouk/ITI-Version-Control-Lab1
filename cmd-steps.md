# Create new repo
git init

# Add github repo
git remote add origin https://github.com/Mahmoud-Matouk/ITI-Version-Control-Lab1

# Add new file and push to github
git add cv.txt
git commit -m "first commit"

# Push to github
git push -u origin main

# change the cv.txt to Eng-Mahmoud-Matouk.txt
mv cv.txt Eng-Mahmoud-Matouk.txt

# commit changes to github
git add .
git commit -m "updated cv name"
git push
