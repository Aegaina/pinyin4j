pinyin4j
========

#### 项目来源
* <http://sourceforge.net/projects/pinyin4j> （原始项目）
* <https://github.com/belerweb/pinyin4j> （二次封装，但已经不维护了，有部分缺陷）
  - QQ Group: 479540440
* <https://github.com/wnjustdoit/pinyin4j> （整合bug修正）
* <https://github.com/zhangethan/pinyin4j> （整合bug修正）

### Download ###
Download the jar via maven:
```xml
        <dependency>
            <groupId>io.github.zhangethan</groupId>
            <artifactId>pinyin4j</artifactId>
            <version>2.6.1</version>
        </dependency>
```

### 多音字识别 ###
在pinyin4j的基础上添加了多音字识别，带近一万个多音词，但是这远远不够，所以用户可设置外挂词库	

### 外挂多音词库 ###
用户配置的外挂词库会覆盖系统中相同词的读音,可用于纠错

配置方式很简单,只需要配置路径即可 
```
MultiPinyinConfig.multiPinyinPath="/Users/yiboliu/my_multi_pinyin.txt"
```

格式同系统的多音词库,如: 
```
吸血鬼日记 (xi1,xue4,gui3,ri4,ji4)
```