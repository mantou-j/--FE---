# --FE---
飞企互联-FE企业运营管理平台-文件上传
```
漏洞描述：
飞企互联-FE企业运营管理平台 /servlet/uploadAttachmentServlet接口处存在文件上传漏洞，未经身份验证的攻击者可以利用此漏洞上传恶意后门文件，获取服务器权限，进而控制整个web服务器。
影响版本：
version < 7.0
fofa语法：
FOFA：app="FE-协作平台"
```
访问漏洞URL，/servlet/uploadAttachmentServlet，出现如上响应，默认存在漏洞。
![image](https://github.com/user-attachments/assets/cc0fb1a9-db86-43f1-b272-96f7d56a42cb)
