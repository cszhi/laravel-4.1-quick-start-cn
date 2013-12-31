laravel-4.1-quick-start-cn
=================

这是一个 laravel-4.1 的完整包（包含了 vendor 目录），常用的源码已经补充中文注释，方便大家快速的开始学习和体验 laravel 框架。

**注意：** 此项目在原始的 laravel 基础上加入了一些辅助元素，本质上并没有对框架核心做任何变动。如果你需要原始的“完整包”，这里向大家推荐 **痛在远方** 为大家打包的项目 [github.com/maliang/complete-laravel4](https://github.com/maliang/complete-laravel4)。

---

- [本项目加入的辅助元素](#difference)
- [Demo](#Demo)
- [学习资料推荐](#)
- [相关开源项目推荐](#)

---


<a name="difference"></a>
## 本项目加入的辅助元素

- 约定了自定义函数库引入的位置。
- 约定了视图别名定义的位置。
- 对项目的静态资源路径做统一管理。
- 增加 migrate 数据库迁移的 MySQL 注释支持，详细内容请参阅这篇博文：[让 Laravel 4.1 的“数据库迁移”支持 MySQL 字段注释](http://my.oschina.net/5say/blog/186017)。
- 引入 laravel-debugbar 调试工具栏。
- 更多详细信息请点击 [different.md](mdDoc/different.md) 查看。

## Demo

- 短链生成[点击查看说明](mdDoc/demoUrlShortened.md)
  - 源于 **袁维隆** 的 *[Laravel4快速上手教程](http://beta.zexeo.com/course/3) 19-22 讲* 稍做改动，建议配合视频学习。