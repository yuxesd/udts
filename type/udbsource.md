

# UDB源

UDTS支持UDB作为数据传输数据源，暂时仅支持UDB MySQL版本。

## UDB MySQL源填写表单

| 参数名   | 说明                                                         |
| -------- | ------------------------------------------------------------ |
| IP       | 内网地址需要填写VPC和子网信息。 |
| 数据库名 | UDB数据库名称                                              |
| 端口     | UDB连接端口                                                |
| 用户名   | UDB连接用户名                                              |
| 密码     | UDB数据库对应用户密码                                      |
| 表名     | UDB传输表名，若不填，系统默认为整库迁移                    |

