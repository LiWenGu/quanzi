圈子账单导出，用于网易有钱导入

fuck，圈子账本导出还要开通会员？我多年的辛苦记账最后嫌弃你记账不行，换个记账软件还要被收割个傻吊会员费？会员还至少是3个月起买。。。

登录账号访问：https://www.jizhangapp.com/account 
F12 检查 network 的请求记录，然后找到类似：
https://quanzi.jizhangapp.com/weixin/h5/book/5e56a76b-7a67-4167-a1c3-77559a8e52d1?list=5e56a76b-7a67-4167-a1c3-77559a8e52d1 的请求，
得到一大串字符串。

本工具就是将圈子账本的字符串转为网易有钱可接受的导入excel文件
