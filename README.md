# 学习ionic4
# 搭建环境：
1.	安装nodeJs：https://nodejs.org/zh-cn/<br>
推荐使用yarn替代npm：https://www.yarnpkg.com/zh-Hans/
2.	安装angular-cli：npm install -g @angular/cli
3.	安装ionic-cli: npm install -g ionic
4.	创建gitHub项目（适合个人学习用）<br>
5.	创建gitLab项目（适合公司开发工作用）<br>
6.  注册ionic-pro账户：https://dashboard.ionicframework.com（每个开发者都要注册的）<br>
7.	创建ionic-angular项目：ionic start myApp --type=angular<br>
### 安装 ionic-pro的
ionic-pro其实很好，但不花钱买服务的话（$30/月），就别安装了<br>
如果在创建项目时，选择了安装ionic-pro，当cli运行时，会提示连接哪个代码管理账户（gitHub、ionic-pro）<br>
选择ionic-pro连接的是已创建好的ionic-pro项目，会出现选择在ionic-pro网站新建项目还是连接在ionic-pro网站上已有的项目，但这个不花钱买服务，就没啥用，推荐个人使用github<br>
选择github连接的是github项目，然后会显示出github项目列表，选择刚创建的项目<br>
### 不安装 ionic-pro的
开发app时，用不上ionic-pro，只有花钱买了服务，后期公司在管理、发版app时，才会体会到ionic-pro的好处<br>
8.	下载Ionic DevApp软件，并用ionic-pro账户登陆app<br>
https://ionicframework.com/docs/pro/devapp/#download-the-devapp<br>
9.	启动PC端：ionic serve<br>
10.	打开Ionic DevApp可以同步看到在PC端的更改，ionic默认使用8100端口，如果同时启动多个ionic项目，ionic会自动修改端口，而且在Ionic DevApp里也都能看到
### 结合gitLab，上传新项目
本地和gitlab上都新创建ionic项目后，根据git的操作方法，执行代码管理即可<br>
1. 执行 git remote add origin git@gitlab.com:lijiadashaoye/withgitlab.git；将项目添加gitlab地址<br>
2. 执行 git commit -m "Initial commit" 和 git add README.md；添加初始提交说明<br>
3. 执行 git push -u origin master；将项目提交到gitlab；<br>
### clone项目
1. git clone https://github.com/lijiadashaoye/ionic4.git
2. 打开项目，安装依赖包：yarn
3. 启动项目：ionic serve
### 公司花钱买ionic-pro的
1. 创建项目时，选择安装ionic-pro<br>
2. 创建项目时，选择不安装ionic-pro，然后，执行：ionic link，可以在ionic-pro新建项目<br>
3. 执行 git commit -m "Your Awesome Changes"；添加在ionic-pro里的提交初始说明<br>
4. 执行 git push ionic master；将项目提交到master分支<br>
后续的操作没做过，就不说了

