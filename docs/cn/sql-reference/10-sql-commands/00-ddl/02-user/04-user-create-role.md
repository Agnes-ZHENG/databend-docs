---
title: CREATE ROLE
sidebar_position: 5
---

创建一个新角色。

创建角色后，您可以向角色授予对象权限，为系统中的对象启用访问控制安全。

另请参阅：[GRANT](10-grant.md)

## 语法

```sql
CREATE ROLE [ IF NOT EXISTS ] <role_name> [ COMMENT = '<string_literal>' ]
```
## 示例

```sql
CREATE ROLE role1;
```