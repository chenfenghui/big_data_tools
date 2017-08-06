# 基本介绍
### 分布式版本控制系统根本没有“中央服务器”，每个人的电脑上都是一个完整的版本库，这样，你工作的时候，就不需要联网了，因为版本库就在你自己的电脑上。
### 既然每个人电脑上都有一个完整的版本库，那多个人如何协作呢？
### 比方说你在自己电脑上改了文件A，你的同事也在他的电脑上改了文件A，这时，你们俩之间只需把各自的修改推送给对方，就可以互相看到对方的修改了

# 命令
git init
git add  1.txt
git commit  -m "修改信息"
git push -u origin master #将本地修改提交到远程

git pull  origin master #将远程修改提交到远程本地
git clone https://github.com/chenfenghui/big_data_tools.git
