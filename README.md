# Youdata Platform

### Quick Start

1. 使用`SSH协议`克隆项目，需先[添加ssh key](https://g.hz.netease.com/profile/keys)，之前没生成过可参考[如何生成ssh key](https://g.hz.netease.com/help/ssh/README)

2. 更新项目相关子模块(需要申请相应repo的权限)：
  ```
  git submodule init
  git submodule update
  ```

3. 安装依赖
  ```bash
  npm config set registry https://registry.npm.taobao.org # 推荐使用淘宝源
  npm config set @netease:registry http://rnpm.hz.netease.com # 配置公司私有npm仓库
  npm config set @youdata:registry http://rnpm.hz.netease.com
  npm install # 或者 npm i
  ```

4. `npm run webpack`打包

5. `npm start`运行web server，项目运行在 http://127.0.0.1:7007


### Tips

> * 若目录无logs文件夹会报错，需手动创建
> * 首次commit前，请配置git用户名及邮箱
```
  git config --global user.name xyz
  git config --global user.email xyz@corp.netease.com
```

### Doc

* [前端基础架构](https://g.hz.netease.com/youdata/Platform/blob/develop/doc/client/%E5%9F%BA%E7%A1%80%E6%9E%B6%E6%9E%84.md)
* [Wiki](https://g.hz.netease.com/youdata/Platform/wikis/pages)