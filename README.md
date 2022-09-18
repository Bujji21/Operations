$ git rm --cached giant_file
# Stage our giant file for removal, but leave it on disk

git commit --amend -CHEAD
## Amend the previous commit with your change

# Push our rewritten, smaller commit
git push

