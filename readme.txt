the file is test by study Git
no message!!
add online text "你好 这个是文件现在是在测试 学习Git"
add “文件” 	 //添加文件
commit -m "介绍" //提交文件
commit -a 	 //提交所有文件
现在测试修改 
git diff '文件名'//查看修改的内容
再次测试 添加文件 为下一步 退版本做准备 Bsah Shell 输入的 
我是傻子啊 我是windows电脑啊 可以直接在可视化界面修改文件啊  现在测试GUI 修改文件
git status 版本状态
git log 操作日志
git reflog 命令日志
git reset --hard 本地版本切换

创建ssh key 用作远程仓库的密码
ssh-keygen -t rsa -C "邮箱" 后面直接全部回车即可 不需要密码 
git remote add origin git@github.com:用户名/需要链接仓库的名字.git
origin 是仓库的命名 以后做相关操作需要使用


把本地推送到 远程仓库 origin
git push -u origin master //第一次推送

之后推送就不需要加 -u 了直接使用
git push origin master //上传到远程仓库

