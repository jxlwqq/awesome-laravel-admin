# Awesome Laravel-admin [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Laravel-admin 资源精选列表。

[English](README.md) | [中文](README-CN.md)

## 贡献

如果你拥有或者找到了一些能让 Laravel-admin 变得更棒的资源，欢迎提交 PR。

## 目录
* [官方](#官方)
* [扩展包](#扩展包)
    * [工具类扩展包](#工具类扩展包)
    * [视图类扩展包](#视图类扩展包)
    * [字段类扩展包](#字段类扩展包)
    * [网格类扩展包](#网格类扩展包)
    * [样式类扩展包](#样式类扩展包)
* [代码片段](#代码片段)
* [Idea](#idea)
* [文章及教程](#文章及教程)
* [视频](#视频)
* [其他](#其他)
* [项目](#项目)

## 官方
* [Laravel-admin 仓库](https://github.com/z-song/laravel-admin)
* [Laravel-admin 官网](http://laravel-admin.org)
* [Laravel-admin 文档](https://laravel-admin.org/docs/zh)
* [Laravel-admin 演示](http://demo.laravel-admin.org)

## 扩展包

### 工具类扩展包

* [helpers](https://github.com/laravel-admin-extensions/helpers) - 面向开发人员的帮助工具，包含`脚手架`，`数据库命令行`、`artisan 命令行`以及`路由列表` 4 个基础功能
* [config](https://github.com/laravel-admin-extensions/config) - 配置管理工具
* [reporter](https://github.com/laravel-admin-extensions/reporter) - 异常信息存储及查看工具
* [media-manager](https://github.com/laravel-admin-extensions/media-manager) - 本地文件管理工具
* [api-tester](https://github.com/laravel-admin-extensions/api-tester) - API 测试工具
* [scheduling](https://github.com/laravel-admin-extensions/scheduling) - Laravel计划任务管理工具
* [redis-manager](https://github.com/laravel-admin-extensions/redis-manager) Redis 管理工具
* [log-viewer](https://github.com/laravel-admin-extensions/log-viewer) - 日志查看工具
* [backup](https://github.com/laravel-admin-extensions/backup) - 数据备份工具
* [phpinfo](https://github.com/laravel-admin-extensions/phpinfo) - phpinfo 信息查看工具
* [translation](https://github.com/laravel-admin-extensions/translation)
* [messages](https://github.com/laravel-admin-extensions/messages)
* [composer-viewer](https://github.com/laravel-admin-extensions/composer-viewer) - Composer 包查看工具
* [env-manager](https://github.com/laravel-admin-extensions/env-manager) - Env 环境变量管理工具
* [id-validator](https://github.com/laravel-admin-extensions/id-validator) - 验证中国大陆居民身份证、港澳居民居住证以及台湾地区居民居住证  
* [file-browser](https://github.com/laravel-admin-extensions/file-browser) - 一个简单的文件浏览扩展
* [lock-screen](https://github.com/laravel-admin-extensions/lock-screen) - 后台锁屏  
* [auth-attempts](https://github.com/laravel-admin-extensions/auth-attempts) - 登录添加图片验证码
* [airan587/alioss-form](https://github.com/airan587/alioss-form) - 上传文件至阿里云对象存储OSS

### 视图类扩展包

* [chartjs](https://github.com/laravel-admin-extensions/chartjs) - Chartjs 图表

### 字段类扩展包

#### 代码编辑器
* [clike-editor](https://github.com/laravel-admin-extensions/clike-editor) - 类 C 语言编辑器
* [python-editor](https://github.com/laravel-admin-extensions/python-editor) - Python 语言编辑器
* [php-editor](https://github.com/laravel-admin-extensions/php-editor) - PHP 语言编辑器
* [js-editor](https://github.com/laravel-admin-extensions/js-editor) - JavaScript 语言编辑器
* [css-editor](https://github.com/laravel-admin-extensions/css-editor) - CSS 语言编辑器
* [json-editor](https://github.com/laravel-admin-extensions/json-editor) - JSON 数据编辑器

#### 富文本编辑器
* [summernote](https://github.com/laravel-admin-extensions/summernote) - Summernote 富文本编辑器
* [wangEditor](https://github.com/laravel-admin-extensions/wangEditor) - wangEditor 富文本编辑器 v3
* [wangEditor2](https://github.com/laravel-admin-extensions/wangEditor2) - wangEditor 富文本编辑器 v2
* [simditor](https://github.com/laravel-admin-extensions/simditor) - Simditor 富文本编辑器
* [ckeditor](https://github.com/laravel-admin-extensions/ckeditor) - CKEditor 4 富文本编辑器
* [UEditor](https://github.com/laravel-admin-extensions/UEditor) - 百度 UEditor 富文本编辑器
* [Quill](https://github.com/laravel-admin-extensions/quill) - 为兼容性和可扩展性而构建的现代 WYSIWYG 编辑器

#### Markdown 编辑器
* [simplemde](https://github.com/laravel-admin-extensions/simplemde) - SimpleMDE Markdown 编辑器

#### 其他
* [china-distpicker](https://github.com/laravel-admin-extensions/china-distpicker) - 基于 Distpicker 的中国省市区三级联动选择组件
* [star-rating](https://github.com/laravel-admin-extensions/star-rating) - 基于 BootStrapStarRating 的评分组件
* [daterangepicker](https://github.com/laravel-admin-extensions/daterangepicker) - 基于 daterangepicker 的时间选择组件
* [typeahead](https://github.com/laravel-admin-extensions/typeahead) - 输入框自动补全
* [cropper](https://github.com/laravel-admin-extensions/cropper) - 图片裁剪组件
* [large-file-upload](https://github.com/laravel-admin-extensions/large-file-upload) - 大文件上传工具
* [bavix/laravel-admin-leaflet](https://github.com/bavix/laravel-admin-leaflet) - OpenStreetMap 组件

### 网格类扩展包

* [grid-lightbox](https://github.com/laravel-admin-extensions/grid-lightbox) - 为 Grid 加上 lightBox 展示功能的组件
* [sparkline](https://github.com/laravel-admin-extensions/sparkline) - jQuery Sparklines 迷你图表
* [media-player](https://github.com/laravel-admin-extensions/media-player) - 视频/音频播放器

### 样式类扩展包

* [material-ui](https://github.com/jxlwqq/material-ui) - 基于谷歌 Material Design 设计风格的 UI 扩展包

## 代码片段

存放在 GitHub Gist 上的代码片段：

* [表单字段前后端双重验证](https://gist.github.com/jxlwqq/3687b809d83761db23bc437dc901c104)
* [表单字段并列排布](https://gist.github.com/jxlwqq/959d9310d2e78963c02b1f6151942ffb)
* [API 路由的最佳实践](https://gist.github.com/jxlwqq/65897e4120ecbc5d7b0e5aaf6f89b2fc)
* [基于当前年月自动创建上传目录](https://gist.github.com/jxlwqq/788470f94ae6cf8823a33fc12bfae94a)

## Idea

有一些能让 Laravel-admin 变得更棒的想法或思考，但出于一些原因，暂时没有实现：

- [ ] 微信公众号管理工具
- [ ] 地图工具
- [x] 图表工具
- [ ] 多后台
- [ ] 系统监控工具
- [ ] 日历工具
- [ ] 上线部署工具
- [ ] 分步表单
- [ ] 二维码生成器

## 文章及教程

[开发扩展教程](http://laravel-admin.org/docs/#/zh/extension-development)

## 视频

* [快速搭建管理后台（基础安装）](https://laravel-china.org/courses/laravel-package/quickly-build-management-background-encorelaravel-admin/2356)

## 其他

期待你的 PR。

## 项目

正在使用 Laravel-admin 的项目或网站：

* [华大科技](http://bgitechsolutions.com/)
