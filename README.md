# Web_HW1
for the first part of question 3 we should use git commit -- amend and for the second part we should use git filter-branch --index-filter "git rm -rf --cached --ignore-unmatch path_to_file" HEAD
For the third part we can use git diff and put it in .patch file and send the .patch file to your friend and then your friend should apply the git patch. 
git diff > my_custom_patch_file.patch  |  git apply patch_file.patch.
Another way is using ssh , with the ssh access you can push, pull, fetch between computers.
