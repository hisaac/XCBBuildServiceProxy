# Welcome!

![Jean-Luc Picard waves begrudgingly at you, the viewer](picard-wave.gif)

Hello, and welcome to my personal fork of the `XCBBuildServiceProxy` repo!

This branch was created so that I could delete the `main` or `master` branch from my fork to limit confusion. If you too would like to create a branch like this, with no git history, here are the steps!

1. Create an orphan branch with no git history:

	```shell
	git checkout --orphan <branch-name>
	```

1. Delete everything in the repo, except the `.git/` directory.
1. Create your README.md.
1. Commit and push your changes as you would normally for a new branch:

	```shell
	git commit -m <message>
	git push -u <remote-name> <branch-name>
	```

1. In GitHub's web UI, navigate to your fork's settings, and set the default branch to your newly created one.
1. Delete the `main` or `master` branch from your fork.
