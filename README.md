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
