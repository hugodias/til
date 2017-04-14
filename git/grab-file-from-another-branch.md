# Grab a file from another branch

This I learned from Thoughbot. You can grab a file from another branch by using the `checkout` command.

Let's say you created a branch for some experimentation in a new API. Couple days later you decided to abort this PR and go by another way.

This new PR may need a file from that old branch, so what you do?

```git
$ git checkout old-branch app/service/awesome.rb
```
