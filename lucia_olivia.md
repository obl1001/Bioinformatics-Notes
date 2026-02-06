# Bioinformatics Notes (GEN 711/811)

## Lab 2 (1/30/26)
- Set Ctrl+Enter keybinding
- Tested echo command
- Created GitHub repo Bioinformatics-Notes
- Cloned repo to RON
- Generated SSH key and added to GitHub
- Verified with ssh -T git@github.com

## Lab 3 (2/6/26)

### 1. Three ways to return to home directory from untrimmed_fastq
1. cd ~
2. cd
3. cd /home/users/obl1001

### 3b. How many programs in /bin?
1624

### List files in /bin using a single ls command
Start with the letter c: ls /bin/c*
Contain the letter a: ls /bin/*a*
End with the letter o: ls /bin/*o
Contain the letter 'a' or the letter 'c': ls /bin/*[ac]*

### Find command in history
history | grep "\.fastq"
