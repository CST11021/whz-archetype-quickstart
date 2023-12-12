一、在github上创建工程
    步骤介绍：
    1、点击你的GitHub头像，选择下拉框中的“Settings”
    2、选择左侧菜单的“Developer settings”一项
    3、选择“Personal access tokens”
    4、点击“Generate a personal access token”
    5、把以下选项全部勾选，然后点击下方绿色按钮，便可生成一个token
    详细步骤参见：https://www.jb51.net/article/195664.htm

二、执行如下命令将本地工程提交到远程仓库
git init
git add .
git commit -m "first commit"
git remote add origin https://${accessToken}@github.com/CST11021/${工程名称}.git
git push -u origin master


git init
git add .
git commit -m "first commit"
git remote add origin https://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@github.com/CST11021/whz-archetype-quickstart.git
git push -u origin master
