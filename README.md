# clash-rule

自用clash meta规则

规则源自：

[Loyalsoldier/clash-rules](https://github.com/Loyalsoldier/clash-rules)

[ACL4SSR/ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)

[blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)

**等**多方规则，并依据个人情况进行调整更改

## 如何使用？

【针对没有自建订阅，自建订阅者也不用看】

1、打开订阅转换网站

警告⚠️：订阅转换网站有风险，无论什么情况下都推荐自建，本教程仅为参考。

https://id9.cc/

https://suburl.v1.mk/

https://acl4ssr-sub.github.io/

三个都是一样的

2、在订阅链接处输入机场订阅，如有多个机场订阅通过换行区分

![img](./img/1.png)

3、客户端选择需要转换的目标

4、远程配置随便选一个，本项目即为远程配置，因为不在默认列表中，需要生成最终链接后再替换config

5、后端地址即为订阅转换后端提供者，一般来说大网站的默认都是比较靠谱和相对安全的（存疑)

6、输出文件名为配置文件命名，自己根据需要写，默认为config.yaml

7、点击生成订阅连接，复制出来，将config=xxxxxxxx进行替换例如：

https://sub.id9.cc/sub?target=clash&new_name=true&url=https%3A%2F%2FXXX.XXX%2F&insert=false&config=aaaaa&filename=TEST&emoji=true&list=false&tfo=false&scv=false&fdn=false&sort=false

替换为

https://sub.id9.cc/sub?target=clash&new_name=true&url=https%3A%2F%2FXXX.XXX%2F&insert=false&config=bbbbb&filename=TEST&emoji=true&list=false&tfo=false&scv=false&fdn=false&sort=false

其中&符号为不同参数的分割。

本项目config为：

```http
https%3A%2F%2Fraw.githubusercontent.com%2Futopeadia%2Fmyclashrule%2Fmain%2Fclash-rule.ini
```

miniconfig(用于苹果移动设备，限制网络扩展内存占用)

```http
https%3A%2F%2Fraw.githubusercontent.com%2Futopeadia%2Fmyclashrule%2Fmain%2Fclash-rule-mini.ini
```

8、将最终订阅链接添加到clash客户端即可使用。
