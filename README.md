# CloudflareScanner

本项目可以测试Cloudflare节点接入速度

程序运行完毕后，结果会保存在当前目录的`result.csv`下

## 注意事项
#### 协程数请不要调过1000，否则容易出现较大误差
#### 编译选项为 `go build`
#### 您可在release界面下载或编译运行
到你们都在扫ip ，自己码了一个cf的高效扫描器
https://github.com/Spedoske/CloudflareScanner
记得把ip.txt和程序放在一个文件夹下面

后续计划：添加下载测速功能
