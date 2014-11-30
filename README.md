SpigotBuildOnTravis
===================

When your lazy like me and dont want to build them your self.

NOTE
=====

Do not use this on a public repo under github. These builds have to be for you/your server only.

Setup
=====
1.Download this repo and its travis.yml file
2.Make new repo (private) for auto making builds for spigot.
3.Put the travis.yml file in it and rename it to .travis.yml
4.Setup in travis CI a enviromental variable for "GITHUB_OATH_TOKEN" and have it equal a OAUTH key that has perms for "repo"
5.Commit it.
6.To get a Spigot.jar Go under releases under the github repo and click the New release, Name it, Wait 5 mins, Enjoy a Spigot Jar freshly built!