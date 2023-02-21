# OneNote 字数统计

读取用 OneNote 导出的 (多个).one 文件，统计(多个)分区下 每个页面的字数(包括中文字数和非中文词数)，最后输出到 Excel 中.

结果和用Word查看的大致相同（我只测试了图文和表格的情况）。

## 使用方法

电脑上要装有 OneNote 桌面版。

```shell
./main.exe <path>
```

`path`为.one 文件的路径。

wx号: wxid_lvt0x8d5eyso22