
# Password Checker

A short script written in python that scrapes data from https://haveibeenpwned.com, a website that checks if your password has ever been hacked. Running correctly the script, it scrapes data from this website and based on it shows you the answer.


## Installation

Install password_checker with git clone

```bash
  git clone https://github.com/fabilier228/Password_checker.git
  cd Password_checker
```
    
## Usage/Examples

```bash
py src/main.py password1 password2 ... lastpassword
```
## Result

```bash
password1 was found 3339722 times... You should change 
password2 was found 266856 times... You should change 
lastpassword was found 635 times... You should change 
```
