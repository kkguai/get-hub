# get-hub
git config --global user.name  //配置姓名</br>
git config --global user.email  //配置邮箱</br>
git config --list  //查看配置信息</br>
git init 	//初始化本地仓库</br>
git status 	 //查看文件状态</br>
git add 文件名 	//添加某个文件到暂存区，如果写 . 代表当前文件夹下所有的文件、</br>
git commit -m 日志说明   //提交到本地仓库</br>
git log    //查看提交记录</br>
git checkout 文件名    //撤销，让暂存区文件覆盖工作区间文件</br>
git rm --cached 文件名   	//在暂存区移除相应文件</br>
git reset --hard 提交ID  	//恢复到指定版本</br>
git branch      //查看分支</br>
git branch develop  //创建分支</br>
git checkout 分支名  //切换分支</br>
git merge  //合并分支</br>
git branch -d 分支名称  //删除分支</br>
git clone 地址 //克隆远程仓库</br>
git push 地址 分支名  //往服务器推送</br>
git pull 地址  //将服务器代码拉取到本地</br>
git remote add 名称 地址 //给地址取别名</br>
git push -u origin master  //-u的参数让git记录信息，下次只需要 git push 就能进行提交</br>
ssh-keygen  //生成一对密钥</br>
