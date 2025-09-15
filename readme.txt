Semana_It120
(This repository contains multiple branches with different updates to showcase Git branching.)

mkdir Semana_It120
cd Semana_It120
git init
touch profile.txt education.txt background.txt readme.txt test.py
ls 
notepad profile.txt
notepad education.txt
notepad background.txt
notepad readme.txt
notepad test.py
git add .
git status 
git init
git remote add origin https://github.com/gilbert-ssz/Semana_It120.git
git branch -M main



## Branch 1 (Semana_B1)
- Added Profile.txt
- Added Education.txt with Elementary School and Year Graduated

git checkout -b Semana_B1
notepad profile.txt
git add profile.txt
git commit -m "Added Education.txt with Elementary School and Year Graduated"
git push origin Semana_B1



## Branch 2 (Semana_B2)
- Updated Education.txt
- Added details: Languages, Contact Person, and Address 

cd ~/Semana_It120
git checkout -b Semana_B2
notepad education.txt
git add education.txt
git commit -m "Added education.txt with Languages, Person to be Contact, and Address"
git push origin -m Semana_B2



## Branch 3 (Semana_B3)
- Updated Background.txt with Languages, Contact Person, and Address
- Removed test.py file

cd ~/Semana_It120
git checkout -b Semana_B3
notepad Background.txt
git add Background.txt
git commit -m "Added Background.txt with Languages, Contact Person, Address"
rm test.py
git push origin Semana_B3



## Branch 4 (Semana_B4)
- Updated this readme.txt to summarize all changes from Branch 1 to Branch 3
- removed test.py file

cd ~/Semana_It120
git checkout -b Semana_B4
notepad readme.txt
git add readme.txt
git commit -m "Added Background.txt with Languages, Contact Person, Address"
rm test.py
git push origin Semana_B4



