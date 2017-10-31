# pbcopy on linux

I've used OSX for at least 5 years. That being said, I used to copy things to the clipboard using the pbcopy command.

Now that I use linux I decided to create an alias, with the same name so I do not have to learn another command.

Just put the following code on your `.profile / .zshrc / .whatever` file

PS: Tested on archlinux

```bash
alias pbcopy='xclip -selection clipboard'
```
