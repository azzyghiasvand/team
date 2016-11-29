Please clone this repo, add yourself to the list and push the update. This helps
verify that the permissions are set properly.

```
# This should look something this (you need a gerrit account):
# git clone ssh://nong@ec2-35-164-117-19.us-west-2.compute.amazonaws.com:29418/team
$ git clone <repo url from gerrit>
$ cd team
$ echo <you> >> README
$ git add README
$ git commit -m "Adding <you>"
$ git push origin HEAD:refs/for/master
```

Team:
  - Nong
  - shekar
  - Saurabh
