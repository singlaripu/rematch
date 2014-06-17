
 Ionic App - Rematch
=====================

Install or check node

```bash
$ node -v
```

Install ionic, cordova and ios sdk

```bash
$ sudo npm install -g cordova ionic ios-sim
```

Create project "rematch" with ionic template "tabs"

```bash
$ ionic start rematch tabs
```

Add and build ios platform 

```bash
$ ionic platform add ios
$ ionic build ios
$ ionic emulate ios
```


Add and build android platform

```bash
$ sudo npm install -g appium
$ brew update
$ brew install ant
```

Edit ~/.bash_profile and add java and android sdk path variables

```bash
export ANDROID_HOME=/Applications/Android\ Studio.app/sdk
ANDROID_TOOLS=$ANDROID_HOME/tools/:$ANDROID_HOME/platform-tools
export PATH=$ANDROID_TOOLS:$PATH
export JAVA_HOME=$(/usr/libexec/java_home)
```

Finally 
```bash
$ ionic platform add android
```

