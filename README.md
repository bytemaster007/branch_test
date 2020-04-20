# 开发文档

## 登录功能
1. 开辟一个 feature-login 分支进行开发
2. 开发完毕后合并到 develop 分支

## 列表分支
1. 开辟一个 feature-list 分支进行开发
2. 开发完毕后合并到 develop 分支


## 步骤
1. `$ git branch`
    + 只有个主分支
    + `* master`
2. 新建develop 分支
    + `$ git branch develop`
    + 因为当前分支在master ,新建的 develop分支 会 copy一份 master分支的内容
    + 切换到develop分支
        + `$ git checkout develop`
    + 在 develop分支上 建立项目目录结构
3. 新建 功能分支
    + 当前分支在 develop
    + 我们建立 feature-login 、 feature-list 两个功能分支
        + `$ git branch feature-login`
        + `$ git branch feature-list`
4. 开发对应的功能切换到对应的分支上进行开发
    + 开发登录功能，切换到 feature-login分支上开发
        + `$ git checkout feature-login`
    
