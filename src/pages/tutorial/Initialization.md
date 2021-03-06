---
previousText: '简介'
previousUrl: '/tutorial/introduction'
nextText: '项目结构'
nextUrl: '/tutorial/structure'
disableHtmlPreviews: true
---

# 使用CLI创建初始化项目

## 第一步 使用 yarn create alita 新建项目

```bash
$ cd 你的常用项目目录

$ yarn create alita hero --pc

  create package.json
  create src/pages/index/index.tsx
  create src/pages/index/index.less
  create src/models/index.ts
  create mock/app.ts
  create src/services/api.ts
  create src/app.ts
  create .gitignore
  create config/config.ts
  create src/models/connect.d.ts
  create tsconfig.json
  create typings.d.ts
✔  success
```

> 这里的 `hero` 指的是项目名，你可以输入任意的名字。
> 如果你的命令行打印的日志如上，那就说明你新建项目完成了，如果有其他的错误，可以确认一下，当前目录下是否存在hero文件夹。

## 第三步 切换到项目目录，安装依赖

```bash
$ cd hero
$ yarn
...这个过程需要一点时间
success Saved lockfile.
✨  Done in 170.43s.

```

看到命令行打印success，一般就是安装成功了，但是有时候因为一些网络问题，会出现丢包的情况。所以我们继续验证。

## 第四步 启动开发服务器

```bash
$ yarn start

✔ success webpack compiled in 2s 743ms
 DONE  Compiled successfully in 2750ms                                  10:24:03
  App running at:
  - Local:   http://localhost:8000/ (copied to clipboard)
  - Network: http://192.168.199.195:8000/
```

## 错误说明

- 可能是node版本问题引起的，确认一下你的开发环境。
- 网络问题引起的，知道的，科学上网。或者使用国内源，全局安装tyarn。

