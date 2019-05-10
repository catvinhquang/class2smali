# How to use:
**1. Dependencies**
- **dx**: $HOME/Library/Android/sdk/build-tools/XX.X.X/dx<br>
- **baksmali**: https://bitbucket.org/JesusFreke/smali/downloads/ => rename and move to /usr/local/bin/ after downloaded



**2. Setup environment variable**
- Edit ~/.bash_profile like below:
> export BUILD_TOOL=$HOME/Library/Android/sdk/build-tools/28.0.3/dx<br>
> export PATH=$PATH:$BUILD_TOOL
- Apply changes by: source ~/.bash_profile