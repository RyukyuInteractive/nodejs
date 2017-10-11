## 1. Install NVM (Node Version Manager - Simple bash script to manage multiple active node.js versions)
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.32.1/install.sh | bash
```
## 2. Export `NVM` as global 
```
vi ~/.bash_profile
```
Enter `i` key to go into insert mode, then paste below code into file:
```
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh" # This loads nvm
```
`esc` -> `shift + :` -> `wq`
## 3. Run script:
```
source ~/.bash_profile
```
## 4. Check:  
```
nvm -v
```
## 5. Install lastest node version
To download, compile, and install the latest release of node, do this:
```
nvm install node
```
And then in any new shell just use the installed version:
```
nvm use node
```

Ref: https://github.com/creationix/nvm
