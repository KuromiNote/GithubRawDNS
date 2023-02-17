># Github DNS污染
若遇到Github上传图片无法访问，也许是DNS污染的问题，此文档可以帮助你解决此问题


Github资源文件域名为`raw.githubusercontent.com`
您可以访问[Nslookup在线域名解析](https://ping.eu/nslookup)，在输入框输入`raw.githubusercontent.com`解析此域名的主机IP

随后将IP地址复制到`C:\Windows\System32\drivers\etc\hosts`并在末尾加上空格再接上`raw.githubusercontent.com`，随后再保存即可
**注意**可能会出现管理员权限无法修改hosts文件，这里可以尝试另存为到其他位置，然后再移动并覆盖`C:\Windows\System32\drivers\etc\hosts`，从而修改hosts文件内容
