

请不要传播！请不要传播！请不要传播！

自行检查有无互助池，我之前搬的时候是删除了的，有些没删除可能加密了，也可能没注意，无需配置互助码，账号之间内部互助。


另外涉及开卡均有部分加密。

青龙 config.sh 文件中修改

## ql repo命令拉取脚本时需要拉取的文件后缀，直接写文件后缀名即可
RepoFileExtensions="js py ts"


# 使用说明（待完善）
## 取关店铺和商品
通过设置变量`UN_SUBSCRIBES`来进行`商品一次性取消数量`, `店铺一次性取消数量`, `商品取关忽略列表`, `店铺取关忽略列表`四项内容的自定义设置，以'&'、回车或'\n'隔开。

|      设定项      |   类型   |            说明            | 示例                             |
| :--------------: | :------: | :------------------------: | -------------------------------- |
|  商品取消数/次   |   数字   |     默认20，为0不取消      | 20                               |
|  店铺取消数/次   |   数字   |     默认20，为0不取消      | 19                               |
| 商品取关忽略列表 | JSON数组 | 按商品详情页的商品编号设置 | ["100016814096", "100009667851"] |
| 店铺取关忽略列表 | JSON数组 |       按店铺名关键字       | ["华硕", "丽台京东自营旗舰店"]   |
