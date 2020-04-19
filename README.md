# ANDROID_HOME
Setting ANDROID_HOME on Mac OS X

1. In Terminal:
> nano ~/.bash_profile 

2. Add lines:
> export ANDROID_HOME=/YOUR_PATH_TO/android-sdk

> export PATH=$ANDROID_HOME/platform-tools:$PATH

> export PATH=$ANDROID_HOME/tools:$PATH

3. Check it worked
> source ~/.bash_profile

> echo $ANDROID_HOME
