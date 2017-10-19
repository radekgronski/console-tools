# console-tools
GNU/Linux console tools.


## Tools description
### ci
Does `git add .` and then `git commit -m "CURRENT_BRANCH_NAME: message how long you want even without quotes"`. Recommended for lazy developers who need to have the branch name in their commit messages. Requires Python 3.


## Instruction

Copy or move the script file to /usr/bin
```
sudo cp ci /usr/bin/
```

Add execution permission
```
sudo chmod +x /usr/bin/ci
```

Done. Now you can use it as a regular command wherever you want.
```
ci My commit message.
```


## Tip
You can rename the script as you want and call it by this name.
```
mv ci commit
```
```
commit My commit message.
```
