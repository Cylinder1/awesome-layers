
# 【官方公共层】PHP72

| ARN  |  兼容运行时  | 版本 |
|------|------|--------|
| `acs:fc:{region}:official:layers/PHP72/versions/3` | custom-runtime   | PHP 7.2.8 |

## 快速开始
可以通过控制台或者 Serverless Devs 工具引用该层。

使用`PHP72`层时，需要配置相应的环境变量 (通过控制台创建会自动配置)。
- `PATH` 环境变量需要添加 `/opt/php7.2/bin` 和 `/opt/php7.2/sbin` 目录，注意需要加到`PATH`的最前面
- `LD_LIBRARY_PATH` 环境变量需要添加 `/opt/php7.2/lib`目录

示例如下：
```shell
PATH=/opt/php7.2/bin:/opt/php7.2/sbin:/usr/local/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/opt/bin
LD_LIBRARY_PATH=/code:/code/lib:/usr/local/lib:/opt/lib:/opt/php7.2/lib
```

## 应用示例
待补充

## License
[PHP License v3.01](https://www.php.net/license/3_01.txt)

## 参考信息
维护者：阿里云-函数计算