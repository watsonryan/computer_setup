# computer_setup


### laptop.pkg 

Install all packages currently listed in laptop.pkg
```bash
dpkg --clear-selections
sudo dpkg --set-selections < laptop.pkg
```

Now, get rid of stale packages: 
```bash 
sudo apt-get autoremove
```
