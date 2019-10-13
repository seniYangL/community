##谈码社区

##资料
[Spring 文档](https://spring.io/guides)

[Spring Web](https://spring.io/guides/gs/serving-web-content/)

[GitHub OAuth](https://developer.github.com/apps/building-github-apps/creating-a-github-app/)

[okHttp](https://square.github.io/okhttp/)

[浅谈UML](https://blog.csdn.net/qq_35495763/article/details/80764914)

    口诀： 实箭泛化虚实现
          虚线依赖实关联
          空菱聚合实组合
          项目沟通图常见

[MySQL学习](https://www.runoob.com/mysql/mysql-create-database.html)

##工具

[Visual Paradigm社区版](https://www.visual-paradigm.com/cn/)
##脚本
```sql
CREATE TABLE `user` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `account_id` varchar(100) COLLATE utf8_unicode_ci DEFAULT NULL,
  `name` varchar(50) COLLATE utf8_unicode_ci DEFAULT NULL,
  `token` char(36) COLLATE utf8_unicode_ci DEFAULT NULL,
  `gmt_create` bigint(20) DEFAULT NULL,
  `gmt_modified` bigint(20) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8 COLLATE=utf8_unicode_ci;
```
