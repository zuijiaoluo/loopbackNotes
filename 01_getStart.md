1. npm install -g strongloop   //安装strongloop
2. slc loopback  //创建loopback项目
    输入相应的项目的name等
3. slc loopback:model  //创建模型   自动生成相应的api
4.  输入model name    生成相应的
[?] Enter the model name: person
[?] Select the data-source to attach person to: db (memory)
[?] Select model`s base class (PersistedModel)
[?] Expose person via the REST API? Yes
[?] Custom plural form (used to build REST URL): people
[?] Common model or server only? common
Let's add some person properties now.
5. node . //启动项目    
6. slc // 开启可视化管理（可能需要注册相应的账号，然后登陆）
