git init
git status
git add .
git commit -m "Initial commit with basic files"
git checkout -b BIHAG_B1
git mv Profile.txt.txt Profile.txt
git add Profile.txt
git commit -m "Add additional info to Profile.txt in B1 branch"
git checkout master
git checkout -b BIHAG_B2
git mv Education.txt.txt Education.txt
git add Education.txt
git commit -m "Add college and program info to Education.txt in B2 branch"
git checkout master
git checkout -b BIHAG_B3
git mv Background.txt.txt Background.txt
git add Background.txt
git rm Test.py.txt
git commit -m "Add additional info to Background.txt and remove Test.py in B3 branch"
git checkout master
git checkout -b BIHAG_B4
git rm Test.py
git add Readme.txt
git commit -m "Add Git commands to Readme.txt in B4 branch"
