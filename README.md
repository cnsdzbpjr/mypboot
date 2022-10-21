# PbootCMS

### PbootCMS is a new kernel and permanent open source free PHP enterprise website development and construction management system, is a set of efficient, concise, powerful free commercial PHP CMS source code, can meet the needs of various enterprise website development and construction. The system adopts template tags that are as simple as crying, and as long as you understand HTML, you can quickly develop a corporate website. The official provides a large number of website templates for free download and use, and will be committed to providing the best website development and construction solutions for the majority of developers and enterprises.
* The system adopts efficient, concise and powerful template tags, as long as you understand HTML, you can quickly develop corporate websites;
* The system adopts PHP language development, using self-developed high-speed multi-layer development framework and cache technology;
* The system adopts sqlite lightweight database by default, which can be used directly when put into PHP space, and can choose mysql and other databases to meet various storage needs;
* The system adopts responsive management background to meet the needs of all kinds of equipment management at any time;
* The system supports online upgrade in the background to meet the needs of timely upgrade and update of the system;
* The system supports content model, multi-language, custom form, filtering, multi-criteria search, mini program, APP and other functions;
* The system supports a variety of URL modes and models, columns, content custom address names, to meet the needs of various website promotion and optimization.

##  简单到想哭的模板标签：
```
1、全局标签示意：
{pboot:sitetitle} 站点标题 
{pboot:sitelogo} 站点logo

2、列表页标签示意：
{pboot:list num=10 order=date}
	<p><a href="[list:link]">[list:title]</a></p>
{/pboot:list}

3、内容页标签示意：
{content:title} 标题
{content:subtitle}副标题
{content:author} 作者
{content:source} 来源

更多简单到想哭的标签请参考开发手册...

```

##  主要功能：
* 支持自定义模板
* 支持站点信息后台配置
* 支持无限极栏目
* 支持自定义内容模型
* 支持自定义内容字段
* 支持专题单页内容
* 支持列表内容管理
* 支持内容复制移动
* 支持自定义栏目地址
* 支持自定义内容地址
* 支持多语言区域建站
* 支持手机独立模板
* 支持手机版域名绑定
* 支持首页分页
* 支持页面SEO优化
* 支持在线留言
* 支持幻N组灯片轮播
* 支持友情链接
* 支持自定义表单
* 支持多条件筛选
* 支持多条件搜索
* 支持验证码开关
* 支持留言发送到多邮箱
* 支持API对接
* 支持小程序/APP开发
* 支持Ajax远程获取数据
* 支持自定义标签
* 支持全站伪静态
* 支持前端动态缓存
* 支持系统角色管理
* 支持完整角色权限管理
* 支持多用户在线管理
* 支持系统日志功能
* 支持数据库在线管理
* 支持后台在线升级
* 支持自定义URL模式

##  系统安装：

发布的源码默认采用sqlite数据库，放入PHP（7.0+）空间即可直接使用(不支持php8.0)。 

如果需要启用Mysql版本，请导入目录下数据库文件/static/backup/sql/xxx.sql，同时请注意使用最新日期名字的脚本文件，并修改config/database数据库连接文件信息。

系统后台默认访问路径：http://ip/admin.php   账号：admin   密码：123456，


##  升级说明：

* 使用后台在线升级（推荐）：

支持跨版本升级，会自动升级数据库及代码文件。

* 使用全包升级：

支持跨版本升级，保留config、data、static、template目录，其余全部用新版替换， 同时如果涉及到的中间版本有升级数据库，需要使用群文件数据库脚本升级数据库。


##  授权声明：
1、PbootCMS是免费可商用的建站系统，用户通过官网获取免费域名授权码即算授权成功，并且永久有效。对于已经授权的域名也不存在未来收费的说法，大家可以放心使用。

2、PbootCMS系统允许个人或公司进行任意二开及商用，但是不允许任何形式的破解或绕过系统授权的行为，包括但不限于通过PbootCMS系统建设网站、二次开发、发布衍生版本等情况，对于任何破解或绕过PbootCMS官网授权的行为，我们将保留依法追究法律责任的权力。

3、PbootCMS除了一个授权文件代码外，其它代码全部开源，并使用Apache2开源协议。对于任何基于PbootCMS进行二开的系统，应该遵守Apache2开源协议的有关要求。

4、PbootCMS官方不对使用本软件所构建网站中的文章、商品和其它任何信息承担责任，不管您通过任何渠道下载本软件，您一旦开始安装PbootCMS，即被视为完全理解并接受PbootCMS授权声明的各项条款。 