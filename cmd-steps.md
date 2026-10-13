# create new repo
git init

# add github repo
git remote add origin https://github.com/Mahmoud-Matouk/ITI-Version-Control-Lab1

# add new file and push to github
git add .
git commit -m "first commit"
git push

# rename the cv.txt to Eng-Mahmoud-Matouk.txt
mv cv.txt Eng-Mahmoud-Matouk.txt

# commit changes to github
git add .
git commit -m "updated cv name"
git push

# amend the previous commit
# add some changes to the cv
git add .
git commit --amend -m "updated cv name"
git push
