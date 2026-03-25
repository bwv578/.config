**Manual Sync Step**

```bash
 
 # 0. In dir
cd ~/.config

 # 1. Init
git init

 # 2. Link remote 
git remote add origin https://github.com/bwv578/.config.git

 # 3. Fetch
git fetch origin

 # 4. Reset 
git reset origin/main

 # 5. Commit or restore
 # 5.1 Commit (preserve local conf)
git add -u
git commit -m "** change some config"

 # 5.2 Restore (follow remote conf)
git checkout origin/main -- .
```

