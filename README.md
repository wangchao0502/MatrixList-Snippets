## MatrixList Snippets
Matrix List的Sublime插件

版本号：
v0.0.1

功能：
生成常用的Matrix List代码

---------

### 使用

**js代码前缀为ml-**

- ml-main: 基础Matrix List项目结构, 包括top, filter, list, footer
- ml-main-exp: 基础Matrix List实例代码([来源：专题管理](http://cp.qima-inc.com/youzan/activity/subject)) 
- ml-main-base: 最简Matrix List脚手架
- ml-config: 全局配置
- ml-top: Top区域配置
- ml-top-new: Top区域新建配置
- ml-top-tabber: Top区域导航菜单配置
- ml-top-btns: Top区域按钮组
- ml-filter: Filter区域表单配置
- ml-table: Table配置
- ml-table-exp: Table配置示例代码

**html代码前缀为tml- (templates)**

- tml-top-btns: Top区域按钮组

`注: html模版需要control+space快捷键才能调出提示框, js可以根据输入自动调出`

**api的代码提示为dml- (description)**

- dml-main: 基础说明
- dml-config: config参数列表
- dml-top: top参数列表
- dml-filter: filter参数列表
- dml-form-: 表单元素, text, password, textarea, select, p, radio, checkbox, hidden, date
- dml-table: table参数列表

**js注释模版为cml-**

- cml-main: main文件的注释

### 下一版本

1. 增加常用的Html代码模版
2. 扩充js代码提示
3. 将Matrix List作为npm模块, 支持matrix命令快速创建目录结构和代码模版（分离出的项目）

### 上传Sublime插件

Offical Document: [Submitting a Package](https://packagecontrol.io/docs/submitting_a_package)

Sublime可以通过Package Install快速安装插件, 这些插件通过向[Package Control Channel](https://github.com/wbond/package_control_channel)提交pull request来将你开发的插件放到ST的公共插件库里。前提是ST只支持来自Github和BitBucket的public repository。

### 下载Sublime插件并使用

将该项目clone到您的Sublime Text目录的Package目录下, 即可自动启用(无需重启)

### 插件原理

本插件没什么技术含量, Sublime提供了非常强大的Snippets支持, 通过编写.sublime-completions文件即可在编写代码的时候进行代码提示, 补全功能[Link](http://docs.sublimetext.info/en/latest/reference/completions.html)。
如果需要自行编写牛逼的插件, 可以通过写Python脚本调用[Sublime Api](http://www.sublimetext.com/docs/3/api_reference.html)完成各种牛逼的操作。目前版本只有一个快速插入当前时间的小功能, 大家有需求可以提issue或者pull request给我。

另外sublime还支持用js代码写插件, [传送门](https://github.com/75team/SublimeJS)。但感觉还是直接用原生支持的靠谱一些。

