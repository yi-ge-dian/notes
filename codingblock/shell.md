1. windows下上传密钥到服务器 

 ```shell
 Get-Content $ewnv:USERPROFILE\.ssh\id_rsa.pub | ssh dongwenlong@192.168.140.128 "cat >> .ssh/authorized_keys" 
 ```

2. npm 改源

https://learnku.com/articles/15975/npm-accelerate-and-modify-mirror-source-in-china 

3. windows 查看电脑电源寿命

```bash
powercfg /batteryreport
```

