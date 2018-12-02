## 这是一个基于gulp构建的前端页面模板

1. 使用了gulp 4.0，优化了gulp task的异步处理问题
2. less、autoprefix样式预处理
3. babel-preset-env处理js代码
4. 使用gulp-file-include插件，复用html模板
5. 开发npm run dev，添加了本地服务器和代理，文件变动监听并刷新浏览器
6. 发布npm run build，压缩文件，添加文件md5值防止浏览器缓存
