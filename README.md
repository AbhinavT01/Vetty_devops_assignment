# DevOps Practical Test

## Task 1: Git Basics

### 1. Create a GitHub Repository

- Go to [GitHub](https://github.com/) and create a new repository.

### 2. Create a new branch named `practical-test`


```bash
  cd <repository_name>  
  git branch practical-test
  git checkout -b practical-test
  git add --all
  git commit -m "add hello.txt"
  git push --set-upstream origin practical-test
  git push origin
```
## Task 2 : Basic Linux Commands
```bash
mkdir vettytest
cd vettytest
touch script.sh
open script.sh
```
Add  this script to script.sh
```bash
#!/bin/bash
echo "welcome to DevOps!"
```
Make the script executable and run it 
```bash
chmod +x script.sh
./script.sh
```



