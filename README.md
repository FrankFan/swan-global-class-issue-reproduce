# 百度智能小程序使用 taro-ui 遇到问题重现


## 步骤

1. 通过 `git clone` 下载该 repo;
2. 通过 `npm install` 安装依赖;
3. 通过 `npm run dev:swan` 开启调试模式;
4. 通过百度开发者工具打开该小程序到 `/dist` 目录;
5. 调整百度开发者工具——项目信息——调试基础库版本，进行效果预览;
6. 发现当基础库版本为 `3.40~3.50` 时，页面中 taro-ui 中的button渲染有问题， 缺少样式；
当基础库版本低于`3.40`或者高于`3.50`时，页面均渲染正常。

![](https://img03.sogoucdn.com/app/a/100520146/e8d055bdaae723d2ce4f5eaf913901e0)



![](https://img02.sogoucdn.com/app/a/100520146/50e08e0388b4dd4027b969de2a92a788)


![](https://img04.sogoucdn.com/app/a/100520146/2a93dee231505ec0e0bf84c4603e4704)


