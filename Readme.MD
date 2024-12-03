### Important notes:
everytime you update(commit and push) backend/frontend/or other subprojects in this repository,

you have to make a commit and push , do this to this parent repository as well.

Example:

you are inside backend:

```git commit -m 'some changes
   git push origin branch-name

```
now go back to main folder
```
cd ..
git add backend
git commit -m 'updated some change on the backend'
git push origin branch-name
```