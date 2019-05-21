1. git init只是创建了一个名为.git的隐藏目录，这个目录就是存储我们历史版本的仓库，ls -al 可以查看。
2. 通过git status可以检测当前仓库文件的状态
3. git add 文件名/ 文件路径 “*”或-A代表所有
一般用  git add  .    添加所有

4. git commit -m '备注信息'
5.git remote add origin https://github.com/zhaohaihao... # 添加远程库仓库
6. git push origin master 将代码推至远程就可以了

5. git log 可查到所有提交历史