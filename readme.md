

Related repositories:

```
ghpages	git@github.com:a-pelenitsyn/a-pelenitsyn.github.io.git
github	git@github.com:ulysses4ever/ulysses.mmcs.sfedu.ru.git
origin	ulysses@staff.mmcs.sfedu.ru:~/site-repo.git
origin	git@github.com:ulysses4ever/ulysses.mmcs.sfedu.ru.git
```

Git config:
```
[core]
	repositoryformatversion = 0
	filemode = true
	bare = false
	logallrefupdates = true
[remote "origin"]
	url = ulysses@staff.mmcs.sfedu.ru:~/site-repo.git
	fetch = +refs/heads/*:refs/remotes/origin/*
	pushurl = ulysses@staff.mmcs.sfedu.ru:~/site-repo.git
	pushurl = git@github.com:ulysses4ever/ulysses.mmcs.sfedu.ru.git
	pushurl = git@github.com:a-pelenitsyn/a-pelenitsyn.github.io.git
[branch "master"]
	remote = origin
	merge = refs/heads/master
	rebase = true
[remote "github"]
	url = git@github.com:ulysses4ever/ulysses.mmcs.sfedu.ru.git
	fetch = +refs/heads/*:refs/remotes/github/*
[submodule "Papers"]
	active = true
	url = https://github.com/ulysses4ever/Papers.git
[remote "ghpages"]
	url = git@github.com:a-pelenitsyn/a-pelenitsyn.github.io.git
	fetch = +refs/heads/*:refs/remotes/ghpages/*
```

