诗词平仄
-----

## 说明

该目录下收集了`json`文件夹下的诗词平仄数据，且该文件夹下的文件与`json`中的文件一一对应，比如`./json/poet.song.rang.8000.json`对应`../json/poet.song.8000.json`。

不但文件一一对应，文件中的内容也是一一对应的，即`./json/poet.song.rang.8000.json`中数组中的第`n`条和`../json/poet.song.8000.json`数组中的第`n`条对应

#### 为什么没有把该结果和诗词数据放在一起？
为了保持诗词数据的纯洁，并非所有数据都适合塞进去。对于这种非所有人需要的数据，通过一一对应关系，可以很方便的给原诗词扩展数据，同时也保证了原诗词的纯洁度。所以当需要对诗词根据知名度排序的需求时，可以把该数据附加到原有诗词数据上即可。


## 数据形式

每个 JSON 文件1000条记录. 为了举例， 删除了余下999条.

```js
[
  {
    "strains": [
        "○仄仄，仄仄仄仄。",
        "？仄平仄仄仄仄仄仄仄平平○？？？？？？？。"
    ],
    "id": "xx-yy-zz"
  }
]
```
