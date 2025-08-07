If any changes come to this submodule, from Brain project.. use:

cd src/data
git status
git add .
git commit -m "Fix/update in Semaphores"
git push origin data
cd ../../..
git add src/data
git commit -m "Update submodule pointer to latest commit"
git push origin master  # or main