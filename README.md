1.上传到github
进入相应文件目录
设置这个目录是管理目录
git init
将文件添加至仓库
git add .
git add -m 'test'
git add h5.html
备注
git commit -m "wrote a h5.html"
移除之前连接仓库
git remote rm origin
连接github仓库
git remote add origin git@github.com:limyue/learngit.git
上传
git push -u origin master
git push -f

//--------------------------------------------------
1、git add .
2、git commit -m "test"（”test“为分支名）
3、git branch test（创建分支）
4、git checkout test （切换分支）
5、git remote add origin https://github.com/limyue/es6new.git
6、git push origin test

**************************************************************

2.从github下载
git clone git@github.com:limyue/gitskills.git
