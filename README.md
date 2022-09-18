# Clear file from the branch
git filter-branch -f --tree-filter 'rm -f /path/to/file' HEAD --all

