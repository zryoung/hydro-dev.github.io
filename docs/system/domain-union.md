# 多域间联合排名

多域间联合排名可以让一个域在计算域内成员 RP 时同时参考成员在其他若干个域内的表现。

该功能只能由站点管理员使用。

例如在 `domian.union` 表中插入下列信息即可让 `domainId` 为 A 的域在计算 RP 时参考 `domainId` 为 B 和 C 的域中的成员表现：

```json
{ "_id" : "A", "union" : [ "B", "C" ] }
```
