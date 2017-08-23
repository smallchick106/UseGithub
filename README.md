## UseGithub---Git
1. git clone + git的地址
2. touch README.md-- 在仓库中必须有文件才能push
3. git add + 文件名
4. git ci -m "提交信息"
5. git push origin master

## UseGithub---eclipse
1. 创建自己的新项目
2. 右键---team with---share project---git---勾上"Use or create repository or create a new one"
   ----点击下面的项目名---再点击create repository ---Finish.
3. 正常来说项目名上会有一个NO-HEAD
4. 右键项目team with---commit---弹出一个Git staging界面---将所有的Unstaged changes 右键 Add to index ,这样stage change中就有了所有要提交的文件
5. 在commit message中写入提交信息---刚开始可以直接点commit and  push,弹出一个界面,
  - remote name=origin
  - URI = Github项目的git地址,如果使用https 会要输入帐号和密码.
6. 点击next---next--Finish---OK就完成了.
