若在使用git时，出现如下报错
```
ERROR: Repository not found.
fatal: Could not read from remote repository.

 Please make sure you have the correct access rights
 and the repository exists.
 ```
可以尝试使用以下解决方法：
 方法一：
```
git credential-manager uninstall
git credential-manager install
```
方法二：
git push时报错，其他命令均正常
```
git remote set-url origin git@github.com:仓库地址.git
```