# Latex Templates

I will store my Latex templates in this repo. Right now (10/14/20) I only have one template, but I may add more as time goes on.

If you want to make a command for creating a new Latex document, adding the following to your .bashrc or .zshrc file should do the trick:
```shell
function latouch() {
    cp /Users/you/your/path/to/standard.tex ./$1.tex
}
```
Then to make a Latex document in your current folder in terminal, enter
```terminal
latouch documentname
```
