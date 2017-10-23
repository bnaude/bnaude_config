Git Configuration file 
---------------------------

```bash
[alias]
    	# Show all commit tree
    	tree = log --graph --decorate --pretty=oneline --abbrev-commit --all

    	# Update project without merge, remove delete branches
    	update = "!u() { git fetch && git fetch -p -t; }; u"

[core]
    	repositoryformatversion = 0
    	filemode = true
    	bare = false
    	logallrefupdates = true
    	ignorecase = true
    	precomposeunicode = true
    	push = upstream

[color]
    	branch = auto
        diff = auto
        interactive = auto
        status = auto
```

