# HackUSB操作文档

#### 一：HackUSB快速上手

插上HackUSB，打开APP并且开启蓝牙GPS定位服务（Android6.0需要）选择(HackUSB)设备即可。

#### 二：脚本规范

<u>tips:脚本关键词请输入大写</u>

###### 1.键盘

```
使用方法
①单个键盘 eg：
WINDOWS键    --->    GUI
②组合键盘 eg：
WINDOWS+R按键 --->   GUI+R
```

###### 2.输出

```
使用方法
STRING  文本
示例
STRING Hello HackUSB
tips:单句STRING限制256字符，发送长字符，请分割并添加默认延迟 DELAY 10
```

###### 3.延迟

```
使用方法
DELAY   ms
示例
DELAY 1000    //延迟1S
tips:程序脚本默认延时50ms
```

###### 键盘关键词

| 关键词 | 说明         |
| ------ | ------------ |
| REM    | 脚本文件说明 |
| DELAY  | 脚本延时 |
| STRING | 文本输出 |
| ENTER  | 回车 |
| GUI    | WINODWS键 |
| SHIFT  | SHIFT键 |
| ALT    | ALT键 |
| CTRL   | CTRL键 |
| UP     | 上 |
| DOWN   | 下 |
| RIGHT  | 右 |
| LEFT   | 左 |
| PS     | PRINTSCREEN屏幕截图 |
|   LOCK     | 大小写锁 |
| KEY+键值 | KEY A就是按A键 |

#### 三：APP使用

APP三部分：

①键盘模拟	脚本在线实时执行

②实时键盘	实时操控键盘

③脚本云仓库	下载仓库内的脚本

#### 四：仓库说明

此仓库适配HackUSB有趣的脚本。下面包含有趣的脚本以及说明。

###### init

简单并有趣的脚本。

#### 五：关于我们

HackUSB于2020年由几个热爱硬件安全的小伙伴共同组建，因为热爱，所以热爱。

#### 六：感谢





