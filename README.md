# 简介
  分享此`qiankun-demo`项目，仅便于学习和解决项目开发上的问题，demo只使用了VUE框架。项目统一使用最外层`pagekage.json`安装插件来实现项目**一致性**，遇到特定第三方插件单独在项目`pagekage.json`配置

----

## 使用说明

### 安装

```npm install```

```npm run examples:install```

### 运行

```npm run examples:start```

## 目录说明

    root/
      common/          公用模块
        components/    公用组件
      examples/
        main/          基座 -- qiankun
        primary-app/   子应用1
        secondary-app/ 子应用2
      package.json
