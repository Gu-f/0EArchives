# 0EArchives

零异(0E)档案 - 用于记录一些奇幻世界的人、物介绍等等。  
详细介绍见[Website](https://0e.pw)

### hugo_extended 版本安装

建议版本：hugo v0.147.9  
[hugo](https://github.com/gohugoio/hugo/releases)

### Dev

Theme Ver: 2.87.0

#### 拉取主题子模块
```
`git submodule update --init --recursive`  # 初始化并更新子模块  
`git submodule update --recursive --remote`  # 后续主仓如果更新了子模块指针，则使用该命令更新子模块  
`git submodule status`  # 检查子模块状态  

`hugo server --bind="0.0.0.0" --port=12345 -D --baseURL="http://127.0.0.1:12345"` # 开发Server  
```

#### 子模块版本切换
```
`cd themes/blowfish`  # 进入子模块文件夹  
`git fetch --tags`  # 拉取Tag版本号  
`git tag -l`  # 查看Tag版本号  
`git checkout tags/v2.87.0`  # 切换到2.87.0版本  
`git status`  # 确保处于分离状态，显示 HEAD detached at v2.87.0
```

### License

**Apache-2.0 license**

[ZH]  
许可仅适用于原创内容，对于非原创的收录内容，请遵循原协议。  
由于内容来源于网友贡献，对于非原创内容，如无意中侵权，请提交相关原创证明，在[该处](https://github.com/Gu-f/0EArchives/issues)反馈，将会第一时间删除。

[EN]  
The license only applies to original content. For non-original included content, please follow the original agreement.  
Since some of the content is contributed by users, if any non-original material unintentionally infringes upon your rights, please submit proof of authorship
via [this link](https://github.com/Gu-f/0EArchives/issues). We will remove the content as soon as possible upon verification.  

