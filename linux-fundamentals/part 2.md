# Linux Fundamentals Part 2

May 2026

## 🎯 Objective
Learn Linux permissions, users, file searching, and SSH basics.



## 🧠 What I Learned
```

 `chmod` → Changes file permissions
 `su` → Switch user
 `su -` → Switch user with full login environment
 `find` → Locate files/directories
 `grep` → Search text inside files
 `ssh` → Connect to remote machines securely

---
```

 ## Permissions

Example:

```bash
rwxr-xr--
Owner → read, write, execute
Group → read, execute
Others → read only
```

## Commands Used

```
chmod +x file.sh
find / -name notes.txt
grep error log.txt
ssh tryhackme@10.10.10.5
```

## Example Output

```
22/tcp open ssh OpenSSH 7.6
```

## Challenges

Confused between find and grep
Mixed up permissions for group and others


## How I Solved It

Practiced reading permissions in groups of 3
Repeated examples using find and grep

## Personal Insight

Linux permissions were confusing at first, but practicing the breakdown repeatedly helped me understand how access control works in Linux systems.

