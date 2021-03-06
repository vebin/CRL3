﻿﻿# CRL
## 简介
CRL是一个面向对象的轻便型ORM业务框架
博客：http://www.cnblogs.com/hubro/

## 特点

1. 不需要代码生成器生成对象类,按标准方式写即可
2. 依托lambda,实现语法解析转换为等效的SQL查询,完全以编程方式进行查询操作
3. 支持常用查询,GROUP,JOIN,SUM,COUNT
4. 无需维护数据表,CRL运行会自动检查表映射,即使新添加的属性,也能自动识别创建相应的字段
5. 多类型数据库,多库支持,只需在应用层实现逻辑切换
6. 缓存支持,轻松创建本地缓存,原创分布式缓存系统 也很闪亮
7. 动态编译,可将任何查询编译为存储过程(仅MSSQL),让查询效率更高
8. 业务封装,通过可继承结构,实现业务封装和重用,内置业务封装,让开发效率大大提高
9. 文档支持,配套文档示例详细讲解了功能用法,新增特性也会更新体现