Please clone this repo, add yourself to the list and push the update. This helps
verify that the permissions are set properly.

```
# This should look something this (you need a gerrit account):
# git clone ssh://nong@ec2-35-164-117-19.us-west-2.compute.amazonaws.com:29418/team
$ git remote add <repo url from gerrit -> projects -> list -> <project> -> ssh>
$ cd team
$ echo <you> >> README.md
$ git add README.md
$ git commit -m "Adding <you>"
$ git push gerrit HEAD:refs/for/master
```

Team:
  - Nong
  - shekar
  - Saurabh
  - Carey
