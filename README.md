# kill_x5_webview_for_mobileqq_and_wechat

PS:也可以在app自带浏览器内进入http://debugtbs.qq.com选择清除TBS，然后选择强制使用系统内核。

两条命令，让qq和微信的X5webview内核混蛋

安卓7.0之后，系统的webview由chrome执行，这是个令人振奋的好消息，但是由于某些傻逼厂家，自己开发了什么破烂x5，嗯，我说的你懂的，所以，我们要干掉这个破烂，以便让chrome执行。

PS:如何查看是否是x5webview？

在手机qq或者微信里任意打开一个网页，按住，并且往下拖，会显示“由QQ浏览器X5内核提供技术支持”

①打开终端

②输入su获取root权限

③输入命令:rm -rf /data/data/com.tencent.mobileqq/app_tbs

④防止再次生成:touch /data/data/com.tencent.mobileqq/app_tbs

⑤输入命令:rm -rf /data/data/com.tencent.mm/app_tbs

⑥防止再次生成:touch /data/data/com.tencent.mm/app_tbs

⑦打开http://ie.icoa.cn/m 测试，或者在手机qq或者微信里任意打开一个网页，按住，并且往下拖，现在不会显示“由QQ浏览器X5内核提供技术支持”
