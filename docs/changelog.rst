更新日志
=========

v0.2.0 (20171212)
-----------------

该版本是 django_echarts 的第一个Beta版本，要求 pyecharts 版本为 v0.3.0+。

- 更新项目到Beta 状态
- 增加 `echarts_js_content_wrap` 模板标签
- 增加 jinja2 模板引擎接口 `django_echarts.plugins.jinja2` 
- 优化模板标签内部逻辑
- 发布在线文档

v0.1.3 (20170930)
-----------------

- 新增配置访问变量别名DJANGO_ECHARTS_SETTINGS
- 废弃DJANGO_ECHARTS_SETTING
- js下载工具增加请求头部

v0.1.2 (20170918)
-----------------

- 重新组织包结构，区分前后端渲染方式
- 统一视图类接口
- 增加 `process_js_list` js合并函数
- 增加多文件下载支持
- 增加中文版文档
- 整理部分测试代码
- 增加Django分类标记
- 修正Django包依赖名称

v0.1.1 (20170911)
-----------------

- 新增 `SimpleEchartsView` 后端渲染视图类
- 新增 `echarts_container` ECharts容器模板标签
- 重写 `HostStore` 内部逻辑，支持自定义扩展host
- 下载命令支持js_host自定义参数
- `lib_js_host` 和 `map_js_host` 支持 `local_host` 变量引用
- 移除 `echarts_js` 模板标签
- 修正未设置 `settings.STATIC_URL` 时host构建错误的bug

v0.1.0 (20170906)
-----------------

- 新增JS静态文件配置
- 新增远程JS文件下载命令
- 新增模板标签模块
- 新增API文档

v0.0.1 (20170729)
-----------------

- 发布第一个 Alpha 版本