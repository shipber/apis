# apis

统一 API 仓库

### 实现方式

使用 git submodule 引入到项目

```bash
$ git submodule add git@github.com:shipber/apis.git
```

更新子模块

```bash
$ git submodule update
```

创建新接口

```bash
$ cd apis # 进入api仓库
$ git checkout -b feature/test
$ git commit -a "add file"
$ git checkout min
$ git merge feature/test
$ git push
```