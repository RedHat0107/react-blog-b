# react + antd 个人博客 (后端)
## 地址
123.56.15.36:12345/admin

## 说明
本博客是一个react全栈系统的后端管理部分,主要功能包括添加,编辑,查看博客文章,并区分登录用户,只有管理员可以添加和编辑文章;以及包括添加,查看和删除说说. 并对文章和说说和访问量做出相应的统计.可以方便的查看到当前最新的文章和说说等功能.

## 技术栈
react + react-redux + redux-saga + fecth + webpack

## 技术要点
1. 使用antd UI 工具构建页面和图表,实现页面的展示
2. 使用braft-editor实现文本的编辑,react-highlight实现代码高亮
3. 框架基于react
4. 使用react-redux实现组件之间的数据的传递
5. 使用redux-saga和fetch实现异步异步事件的请求
6. 使用mongodb实现数据的存储
7. 使用nodejs编写接口实现后台与前端的数据交互,express框架实现路由的控制
8. 使用webpack打包上线

## 使用
- git clone http://github.com/RedHat0107/react-blog-b.git
- cd react-blog-b
- yarn i
- yarn start