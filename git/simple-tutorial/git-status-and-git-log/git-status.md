# Git Status

Use git status to find out information regarding what files are modified and what files are there in the staging area — it shows other information as well, which we can ignore for now.

Use the following command to see the status:

```bash
git status
```

The status shows that **`demo.txt`** is modified and is not yet in the staging area.  
Now let us add **`demo.txt`** to the staging area and commit it using the following commands:

```bash
git add demo.txt
git commit -m "demo.txt file is modified"
```

