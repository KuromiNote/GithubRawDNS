># Github DNS污染
若遇到Github上传图片无法访问，也许是DNS污染的问题，此文档可以帮助你解决此问题


Github资源文件域名为`raw.githubusercontent.com`
您可以访问[Nslookup在线域名解析](https://ping.eu/nslookup)，在输入框输入`raw.githubusercontent.com`解析此域名的主机IP

随后将IP地址复制到`C:\Windows\System32\drivers\etc\hosts`
