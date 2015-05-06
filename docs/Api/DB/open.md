open
====
`open` &mdash; 打开数据库连接

说明
----
>     void open(void)
> 打开数据库连接。

参数
----
> 没有参数。

返回值
------
> 没有返回值。

范例
----
>
    <!-- 配置文件 -->
    <?xml version="1.0" encoding="UTF-8"?>
    <SEConfigs>
        ...
        <DB>
            <type>access</type>
            <source>Data/DataBase/# Data.asp</source>
        </DB>
        ...
    </SEConfigs>
>>
>
    <%
    SE.module("DB").open()
    %>