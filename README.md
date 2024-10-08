# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题

  \#为标题修饰符， 从1-6级标题， 字体从大到小<br>
  再Markdown 语言中\<br\>表示换行符， 不加默认不换行<br>

## 正文
  正文内容， 直接编辑即可， 如果需要段落， 那么需要首字符缩进<br>
  正式修饰关键 , *斜体特效*,  **粗体特效**  ***粗斜体*** , ~~删除线特效~~ , 一段话中的1`关键字`<br>

## 分割线

写\-\-\-可以表示分割线，与后续的正文分隔

-----

## 引用特效

  使用\>表示引用，  引用分为多级  1-6级
> 1级引用
>> 2级引用
>>> 3级引用

## 列表
  列表分为有序列表与无需列表， 一般用于内容目录,  \* 表示无需列表关键字,  1. 表示有序列表关键字

* FPS设计游戏
  * CSGO
    * Dust2
    * M4a1
    * AK47
  * PUBG
    1. AWM
    2. AUG
  * Apex
* 角色扮演游戏

1. 物理学
   1. 凝聚态物理
   2. 粒子物理
2. 数学

## 表格
  如果要在文档中绘制table , 需要使用|来分隔列， 并且指定内容对齐方式

|姓名|技能|排行|
--|:--:|--:
|张飞|俺也一样|23|
|吕布|认亲|1|
|刘备|扔媳妇|13|

## 插入代码片段
  使用\`\`\`语言，开头，以\`\`\`结束， 之间直接插入代码片段即可

```c
	#include <stdio.h>
	int main(void)
	{
		printf("hello C\n");
	}
```

```bash
	pwd
	echo "xxx"
	cd pwd
	ps aux
```
```cpp
```

## 超链接

  再文档中加入可点击的超链接， 点击后按照指定的地址访问打开新资源

[哔哩哔哩](https://www.bilibili.com "孙贼点击访问")


## 插入图片
  在文件中插入图片，需要指定图片地址，区分本地地址与URL网络地址
  本地图片地址， 外网无法访问， 需要用户将本地图片上传到图床网站 ,生成网络图片的url=https://pic3.com/xxxx/1.jpg
![桌面截图](C://Users//cui88//Desktop//1.jpg "桌面截图")


