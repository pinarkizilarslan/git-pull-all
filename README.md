# Git Pull All

### Git Pull Script
This is a simple .sh script that executes the command ```git pull origin main``` in all subdirectories of a folder.

### Usage
For instance, suppose you have a directory named microapps containing several microapps. While inside the microapps directory, you can update all of its contents by executing the command:

```
bash git-pull.sh
```

This will pull the latest changes from the main branch of each microapp repository.

### Instructions
1. Ensure you have appropriate permissions to execute shell scripts.
2. Place the *git-pull.sh* script in the directory containing the subdirectories you want to update.
3. Navigate to the directory containing the script in your terminal.
4. Run the script using the command mentioned above.

### Note
- This script assumes that each subdirectory corresponds to a separate Git repository.
- It pulls changes only from the main branch. If you need to pull from a different branch, modify the script accordingly.
