# 时间账本: 记录点滴，沉迷数据 :)

本项目想法是基于自己的实际需求而产生的。

一直有写日记的习惯（使用[OneNote](https://products.office.com/en-us/onenote/digital-note-taking-app)），其中有一项就像`today.txt`类似格式的记录方式，然后一个星期，一个月总结统计一次自己特别在意的方面的时长，比如学习。其中存在的问题就是，人工成本还是很大的，而且统计的数据不直观。很早就有写这个项目的冲动，奈何是个前端渣_(:з」∠)_（完善这个项目是我继续学习的动力

曾经也使用过时间管理方面的软件，比如须臾、种树、番茄TODO、时间块（坚持使用最久）等。各有优劣，其中最大的缺点就是只能手机使用；而我现在比较常用的是电脑，我认为打开便签打字时间段，比解锁手机打开软件选中滑动滑块要方便的多；还可以定制自己特殊的需求，比如日历总览，对于我回顾一个星期一个月的所作还是很有必要的。

数据本地化，无需搭建后端，待日后搭建`GitHub Pages`，迁移使用。

## 分析`today.txt`小工具

1. 按照规则填写`today.txt`
2. 命令行输入`npm run data-pre`，小工具将会处理数据，转化为`JSON`格式添加至对应的`public/data/${year}/${month}.json`中，用于页面获取数据。

```
2019.10.5
8.30 睡觉
9.00 洗漱
9.30 吃饭
11.00 学习
...
```

## 更新日志

### [Unreleased] - ????-??-??

#### Added
- 时间年月日分类统计
- 那年今日
- 数据加密

### [0.0.1] - 2019-09-16

#### Added
- 添加分析`today.txt`小工具
- 实现日历的基本功能---查看当天主要事件