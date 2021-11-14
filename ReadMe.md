Restore a lost commit
======
0. Run the following code

```bash
echo 'Important' > file.txt
git add file.txt
git commit -m "Add an important file"
git reset --hard HEAD~1
```
1. A commit containing an important text file was lost
2. Find and restore the lost commit
