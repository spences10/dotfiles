# Dot files

Dot files and configurations, I learned about `.` files from listening to the [toolsday.io][toolsday] podcast with [Chris][chris] and [Una][una]

Great channel for learning about tooling 👍 the podcast was about [Git Tools][git-tools]

This was a pretty cool learning experience for me and I now have a pretty efficient git workflow 🚀

## Chocolatey

If you're a Mac or Linux user then this isn't for you, if you're a Windows user then welcome, this isn't really a dot file but I feel that if I'm setting up a new machine then I will be using all my dot files listed I'll need the software those dot files are used in first!

I found a pretty helpful [post][choco-backup] by Sean Killeen detailing getting a list out of Choco

```shell
clist -lo | Out-File C:\Users\spenc\Desktop\chocolist.txt
```

Installing thhe list will be `cinst packagename1 packagename2 packagenameN`

<!--Links-->
[toolsday]: http://www.toolsday.io/
[chris]: http://twitter.com/chrisdhanaraj
[una]: http://twitter.com/una
[git-tools]: http://www.toolsday.io/episodes/git.html
[choco-backup]: https://seankilleen.com/2014/01/quick-tip-chocolatey-powershell-dropbox-for-package-management-and-backup/


