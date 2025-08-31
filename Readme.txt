git clone <repo-link>
git checkout -b Halasan_B1
git add Profile.txt
git commit -m "Updated Profile.txt in branch B1"
git push -u origin Halasan_B1

git checkout main
git checkout -b Halasan_B2
git add Education.txt
git commit -m "Updated Education.txt in branch B2"
git push -u origin Halasan_B2

git checkout main
git checkout -b Halasan_B3
git add Background.txt
git rm Test.py
git commit -m "Updated Background.txt and removed Test.py in branch B3"
git push -u origin Halasan_B3

git checkout main
git checkout -b Halasan_B4
git add Readme.txt
git rm Test.py
git commit -m "Updated Readme.txt and removed Test.py in branch B4"
git push -u origin Halasan_B4