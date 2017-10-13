# kill_x5_webview_for_mobileqq_and_wechat
两条命令，让qq和微信的X5webview内核混蛋

安卓7.0之后，系统的webview由chrome执行，这是个令人振奋的好消息，但是由于某些傻逼厂家，自己开发了什么破烂x5，嗯，我说的你懂的，所以，我们要干掉这个破烂，以便让chrome执行。

①打开终端
②输入su获取root权限
③输入命令 rm -rf /data/data/com.tencent.mobileqq/app_tbs
④防止再次生成  /data/data/com.tencent.mobileqq/app_tbs
⑤输入命令 rm -rf /data/data/com.tencent.mm/app_tbs
⑥防止再次生成 touch /data/data/com.tencent.mm/app_tbs
⑦打开http://ie.icoa.cn/m测试
