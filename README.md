# bilibili工房收益提现通知&172号卡提现通知

由于B站工房收益到账前需要审核2-3天，到账后才可以提现，并且没有提现通知，所以我突发奇想写了一个提现通知的软件来提醒我提现。（172号卡是次月底可以提现，同样老是忘记按时提现。）

结合Windows的任务计划程序，可以开机登录后就以消息窗口的方式提醒我(如图2)

程序反馈：https://space.bilibili.com/1302624960

---

食用方法：
安装java18.0.2及以上版本的环境，或下载“release”中的java18.0.2，与收益查询.exe在相同目录

1.解压缩

2.打开收益查询.exe

![UI](https://github.com/user-attachments/assets/34930a7f-5717-4ec8-9870-76f71e7397d0)

3.输入对应的cookie或Token后点击“保存”，会自动弹出收益提醒

![收益](https://github.com/user-attachments/assets/8585d879-55ae-4f15-9dfc-0d9a54415bf4)

Cookie和Token依次为：

https://member.bilibili.com/platform/allowance/withdraw
![Cookie1](https://github.com/user-attachments/assets/51906caf-8ad1-46c7-895b-052ab069d2b0)

https://mall.bilibili.com/mall-up-c/shop/settle/query（工房余额和待结算需要通过手机的小蓝鸟抓包获取，其余都可从浏览器f12获取）

https://haoka.lot-ml.com/view/iframe.html
