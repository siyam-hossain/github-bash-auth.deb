
# Log in using Github CLI




### Login and Authentication

For Debian based os


#### Step-1 : Update system
```bash
  sudo apt update
```

#### Step-2 : Install GitHub CLI
```bash
  sudo apt install gh -y
```
#### Step-3 : Log in to GitHub
```bash
  gh auth login
```

#### Step-4 : 
```bash
  What account do you want to log into? 
  ->GitHub.com
  
  What is your preferred protocol for Git operations? 
  ->HTTPS
    ssh
  
  Authenticate Git with your GitHub credentials? 
  -> Yes
  
  How would you like to authenticate? 
  ->Login with a web browser
    Token
```