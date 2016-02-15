# react-native-demo
##mac安装过程中出现的问题：
+ brew install watchman 执行错误 
<pre><code>Warning:You are using OS X 10.11.We do not provide support for this pre-release version.
Warning: You are using OS X 10.11.
We do not provide support for this pre-release version.
You may encounter build failures or other breakage.
Error: Could not create /usr/local/Cellar
Check you have permission to write to /usr/local</code></pre>
解决办法参考：http://superuser.com/questions/940874/homebrew-doesnt-install-new-apps-in-el-capitan

+ npm install -g react-native-cli 执行错误
<pre><code>npm WARN checkPermissions Missing write access to /usr/local/lib/node_modules</code></pre>
解决办法: 没有权限。在命令前面加上sudo，第一次不成功多尝试几次。

##参考
https://facebook.github.io/react-native/docs/getting-started.html#content
