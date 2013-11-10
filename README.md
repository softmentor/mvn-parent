mvn-parent
==========

This is the parent pom for all softmentor maven projects

Usage:
======
1) This has dependency with https://github.com/softmentor/code-analyze project(since this code-analyze artifacts are not available in any public maven repo, you would have to install it locally by first cloning the repo and performing `mvn clean install` on it)

2) Clone this *mvn-parent* repo.

3) Run `mvn clean install` on it.

4) You are ready to use all the projects under softmentor which has this as the parent pom.
