# 已生成好的srt文件在各个版本的文件夹中，可以点进去直接下载

## 自己生成srt方式↓
### 1、自行前往 [安柏网](https://ambr.top/chs/archive/quest) 找到自己要的剧情章节
### 2、打开F12，选择网络，找到类似于这样的接口：https://api.ambr.top/v2/CHS/quest/xxxx
### 3、将此接口的返回内容保存到本地文件，后缀为.json。
### 4、如未安装java11环境，请先安装java11。（已安装java11以上请忽略）
### 5、在release中下载genshin-srt.jar 
### 6、下载完后，前往jar包所在文件夹下，执行该命令
```
java -jar genshin-srt.jar /xxxx/xxx.json
```
### 7、上面的路径换成安柏网上面保存下来的文件路径(绝对路径)
### 8、最后，会分章节保存为srt文件到当前目录
