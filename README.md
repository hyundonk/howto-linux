# howto-linux
Things to remember for my linux machine customization


```
# on MAC
cat ~/.zshrc
bindkey '^[[A' up-line-or-search
bindkey '^[[B' down-line-or-search

# on Linux
cat ~/.inputrc
# Press up-arrow for previous matching command
"\e[A":history-search-backward
# Press down-arrow for next matching command
"\e[B":history-search-forward


JAVA_HOME="/Library/Java/JavaVirtualMachines/jdk-18.0.2.jdk/Contents/Home"
M2_HOME="/Users/hyuk/apache-maven-3.8.6"
PATH="${JAVA_HOME}/bin:${M2_HOME}/bin:${PATH}"
export PATH

```
