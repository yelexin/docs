# 错误代码

----------

错误代码消息格式如下：

``` javascript
    {
        message: '系统繁忙，请稍后再试',
        code: 1000,
        data: null
    }
```

代码  | 描述
----  | ------------
1000  | 系统繁忙，请稍后再试
1001  | 无权限执行此项操作
2000  | 账号异常，需要输入验证码
2001  | 验证码验证失败(验证码错误)
2002  | 月登录限额已用完
2003  | 注册或登录时邮箱格式不正确
2004  | 用户不存在
2005  | 用户已被锁定
2006  | 密码不正确
2007  | 应用名非法
2008  | 已拥有同名应用
2009  | 非法的应用类型
2010  | 需提供操作的应用的ID
2011  | 应用不存在
2012  | 缺少默认用户组
2013  | 非法的应用描述
2014  | 搜索用户时输入格式错误
2015  | 搜索用户时搜索类型非法
2016  | 解密客户端密码出错
2017  | 解析邮件模本的meta_data(宏)命令错误
2018  | 用户无权限修改此项内容
2019  | 修改密码时需要先进行验证
2020  | 尚未登录，无权限访问此请求
2021  | 邮件发送失败，原因：无法获取邮件模版
2022  | 用户邮箱验证失败，原因：无法获取邮件模板
2023  | 用户邮箱验证失败，原因：验证链接已过期，需重新发送
2024  | 项目描述不能超过140个字
2025  | 使用默认邮件服务商出错
2026  | 用户已存在，请不要重复注册
2027  | OAuth注册，但尝试用密码登录，因未设置密码，无法验证，请通过OAuth登录
2028  | 请提供正确的手机号或邮箱
2029  | 密码长度不能少于 6 位
2100  | 注册过于频繁，请稍候再试
2101  | 请提供应用ID
2200  | 该邮箱已存在，请换一个吧
2201  | 请输入原始密码
2202  | 修改的信息不属于当前用户
2203  | 原始密码错误
2204  | 邮箱格式不正确
2205  | 缺少参数：registerInClient
2206  | 登录信息已过期, 需重新登录
2207  | 登录信息有误, 需重新登录
2208  | 请换一个与现有邮箱不同的邮箱吧
2209  | 无权限删除该用户
2210  | 执行了错误的删除操作，可能原因是意图删除不存在的用户，或删除过程中出现了其它错误
3012  | 宏命令执行错误
3013  | 发送邮件错误，未知错误
3014  | 邮件发送失败，原因：无法获取transporter
5000  | 获取订单对应应用失败
5001  | 订单不存在
5022  | 创建订单失败
5023  | 创建支付宝订单失败
5024  | 创建订单失败，未知错误
5025  | 创建订单失败：价格不合法
