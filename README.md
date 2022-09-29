# 小明插件包   

by : [qfys521](https://github.com/qfys521)

<details>  

<summary> 目录(可折叠)</summary>         
 
 
 ---         
 
 
> 1. [简介](#%E7%AE%80%E4%BB%8B)    
>>  - 关于本包   

> 2. [关于小明](#%E5%85%B3%E4%BA%8E%E5%B0%8F%E6%98%8E)   
>>  - CodeThink团队介绍
>>  - 小明介绍   

> 3. [启动脚本](#%E5%90%AF%E5%8A%A8%E8%84%9A%E6%9C%AC)   
>>  - Linux下   
>>  - Windows下   

> 4. [插件介绍](#%E6%8F%92%E4%BB%B6%E4%BB%8B%E7%BB%8D)   
>>  - 必备性安装插件   [->](./plugins/README.md)
>>>   1.Permission   
>>>   2.Essentials   
>>  - 选择性安装插件   [->](./[可选插件]/READNE.md)
>>>   1.xiaoming-plugman   
>>>   2.faweUtilPro   
>>>   3.XiaoMingMinecraft   
>>>   4.qfys521Uitl   
>>>   5.XiaoMing-Tools-Reload   
>>>   6.Nudge   
>>>   7.pixiv   
>>>   8.LexiconsPro   
>>>   9.Process   

</details>

## 简介     
- 关于本包    
本包为小明用户更加方便的使用小明，本包的相关插件以及小明本体的最终解释权归相关插件作者和小明作者所有。   
## 关于小明    
- CodeThink团队介绍   
   CodeThink，中文名「代码思维」，于 2022 年初由椽子成立的技术团队。现正研发包括小明（即时通讯软件机器人适配层）、小明平台（基于小明的插件化框架）在内的多款库和应用程序。         
>   有关`CodeThink`，您可以点击这里 ->   [CodeThink](https://github.com/codethink-cn)         
- 小明介绍         
> 当前新版小明还在精雕细琢中，请您敬请期待。如果想要体验小明，还请您暂且使用旧版，谢谢。           

小明机器人是一款基于 `Mirai` 的插件化、便于上手、简单小巧的通用 `QQ` 机器人框架。           

> 有关`小明`，您可以点击这里 -> [小明](https://github.com/codethink-cn/xiaoming)               
> 有关`Mirai`，您可以点击这里 -> [Mirai](https://github.com/mamoe/mirai)               
## 启动脚本   
 - Windows   
在Windows下，我们推荐您使用以下脚本进行启动:   
``` bat or cmd
chcp 65001
cd ./
java -Dfile.encoding=GBK -Dstdout.encoding=GBK -Dstderr.encoding=GBK -jar XiaoMingHostTerminal-4.8.3.jar
```
这样我们可以尽力避免乱码问题。   
 - Linux   
在Linux下，您无需考虑乱码问题，只需要简单的启动脚本启动即可。
``` sh
cd ./
java -jar XiaoMingHostTerminal-4.8.3.jar
```   

如果在使用过程中提示缺少权限之类的情况，请使用`chmod`命令。
## 插件介绍       
>  `必备性`插件我们会放进小明启动时`默认的插件文件夹`中，而`可选性`插件则会放在`不被小明所加载的文件夹`中。        


 - `必备性`插件   


 | 插件 | 作者 | 收录版本 | 简介 |
 | ---- | ----| ---- | ---- |
 | [Permission](./plugins/) | [Chuanwise](https://github.com/Chuanwise) | 3.0 | `权限组`管理插件 |
 | [Essentials](./plugins/) | [ThymeChen](https://github.com/ThymeChen) | 2.0.11 | `群聊`管理插件 |
 - `可选性`插件   


 | 插件 | 作者 | 收录版本 | 简介 |
 | ---- | ----| ---- | ---- |
 | [xiaoming-plugman](./[可选插件]) | [qfys521](https://github.com/qfys521) | 1.3 | 小明插件信息插件 |
 | [faweUtilPro](./[可选插件]) | [qfys521](https://github.com/qfys521) | 5.0 | FAWE命令提示 |
 | [XiaoMingMinecraft](./[可选插件]) | [Chuanwise](https://github.com/Chuanwise) | 5.5| QQ和MC互通插件 |
 | [qfys521Uitl](./[可选插件]) | [qfys521](https://github.com/qfys521) | 3.5.2-2 | qfys521的小工具 |
 | [XiaoMing-Tools-Reload](./[可选插件]) | [ThymeChen](https://github.com/ThymeChen) | 1.0 | 小明小工具 |
 | [Nugde](./[可选插件]) | [ThymeChen](https://github.com/ThymeChen) | 2.3.1 | 戳一戳 |
 | [pixiv](./[可选插件]) | [ThymeChen](https://github.com/ThymeChen) | 1.3 | 涩图 |
 | [LexiconsPro](./[可选插件]) | [Chuanwise](https://github.com/Chuanwise) | 1.16 | 自定义关键词回复 |
 | [Process](./[可选插件]) | [Chuanwise](https://github.com/Chuanwise) | 1.3.2 | 进程命令 |
