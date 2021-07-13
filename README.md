# E5-Rclone-Actions

用Github Actions每天自动使用Rclone调用OneDrive，使Office E5订阅保持活跃。

注：E5保活皆是玄学，能不能成功谁能知道呢。

# 使用方法

## 一、Fork此仓库
![](http://tu.yaohuo.me/imgs/2020/06/f059fe73afb4ef5f.png)
## 二、设置Rclone配置
添加名为**RCLONE_CONFIG**的变量  
值为Rclone的配置，需要你本地先生成配置，之后打开Rclone配置文件复制出OneDrive的配置  
配置最前面的[od]需要改成[e5] ("od"是在用Rclone添加OneDrive时设置的)  
![](http://sennqm.iwater.pw/images/2020/07/14/notepad_jmSv145s4V.png)

## 三、启用Actions
如图所示开启Actions，**之后再对你自己Fork后的仓库点击Star（不要漏看了这一句）**
![](http://tu.yaohuo.me/imgs/2020/06/34ca160c972b9927.png)
![](http://sennqm.iwater.pw/images/2020/07/14/OdLKp2KEly.png)

## 四、查看运行结果
Actions > E5-Rclone-Actions
