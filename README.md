# 中国地质大学图书馆微信小助手

## 信息
基于 itchat 实现的一个中国地质大学图书馆微信小助手。

## 功能

- 预约图书（图书可借时提醒）
- 查询图书（用图书的id）
- 查找图书（关键字搜索）
- 等待添加，有好的意见可以告诉我哟

## 使用
添加 dashuaidexiaokeai 微信账号为好友，就可以向他发送指令来进行操作了。
图书的id号指的是在图书馆网站图书详情页例如 http://202.114.202.207/opac/item.php?marc_no=0000735000，后面marc_no=后面的数字就是图书的id了。
在使用查找指令时也会得到图书的id哟
指令还有参数之间都要有空格哟
## 指令

- 预约

    预约图书，当图书可借时会得到提醒

    指令：预约 + 图书id（任意个）
    > 预约 0000735000 0000735001

- 取消预约
    取消预约图书

    指令：取消预约 + 图书id（任意个）
    >取消预约 0000735000 0000735001

- 预约列表
    获得当前预约的图书列表

    指令：预约列表
    >预约列表

- 查找
    用关键字查找图书（目前只支持在标题中查找）

    指令： 查找 + 关键字 + 期望得到结果个数（默认10，最好不要太大）
    >查找 机器学习导论 11

- 查询
    用图书id精确查询图书详细信息

    指令：查询 + 图书id（目前只支持一个id）
    >查询 0000735000

- 帮助
    返回帮助信息

    指令：帮助
    >帮助





