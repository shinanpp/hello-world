## 问题1 显示没有关联本地仓库到githubcangku
问题原因：hello world中间有空格，终端无法识别url中间的空格（url是什么意思呢）
解决方法：1.使用“”包裹url
          2.改为hello_world
          
## 问题2  window依旧无法识别url中间的空格
错误代码：fatal: unable to access 'https://github.com/shinanpp/hello 
world.git/': URL rejected: Malformed input to a URL function_
解决方法：重命名GitHub仓库