# ANDROID_HOME
Setting ANDROID_HOME on Mac OS X

1. In Terminal:
> nano ~/.bash_profile 

2. Add lines:

> export JAVA_HOME=$(/usr/libexec/java_home)

> export ANDROID_HOME=/YOUR_PATH_TO/Library/Android/sdk

> export PATH=$PATH:$ANDROID_HOME/emulator

> export PATH=$PATH:$ANDROID_HOME/tools

> export PATH=$PATH:$ANDROID_HOME/tools/bin

> export PATH=$PATH:$ANDROID_HOME/platform-tools

> export PATH=$PATH:/YOUR_PATH_TO/Development/flutter/bin

3. Check it worked
> source ~/.bash_profile

> echo $ANDROID_HOME
