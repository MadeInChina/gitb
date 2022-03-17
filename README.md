# gitb tool for managing multiple git repositories

# How to install

`brew tap MadeInChina/homebrew-taps`

`brew install gitbatch` or `brew install --build-from-source gitbatch`

# How to using

```shell
➜  ~ gitb pull
---------------------gateway---------------------
remote: Enumerating objects: 56, done.
remote: Counting objects: 100% (56/56), done.
remote: Compressing objects: 100% (31/31), done.
remote: Total 38 (delta 19), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (38/38), 5.76 KiB | 196.00 KiB/s, done.
From org.madeinchian/gateway
   abc3af7..7fa0d9e  master     -> origin/master
Updating abc3af7..7fa0d9e
Fast-forward
 pom.xml                                                                | 131 ++++++++++++++++++-----------------------------------------------------------------------------------------------------------------
 org.madeinchian/gateway/GatewayConfiguration.java   |  23 ++++++++++-------------+++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 ---------------------user-service---------------------
remote: Enumerating objects: 124, done.
remote: Counting objects: 100% (124/124), done.
remote: Compressing objects: 100% (63/63), done.
remote: Total 102 (delta 36), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (102/102), 9.45 KiB | 3.15 MiB/s, done.
Resolving deltas: 100% (36/36), completed with 12 local objects.
From org.madeinchian/user-service
   e9a4813..f2d1327  master     -> origin/master
Updating e9a4813..f2d1327
Fast-forward
 pom.xml                                                                                          |  38 ++++++++++++++++++++++----------------
```

