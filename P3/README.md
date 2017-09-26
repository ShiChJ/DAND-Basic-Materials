# P3常见问题汇总

**1. 请问Pages中的Show hisgoty在哪？**

请参阅[此链接](http://onlinehelp.tableau.com/current/pro/desktop/en-us/buildmanual_shelves_pages.html)

**2. 如何进行数据预处理，将Genres等分成多列？**

请参阅[此链接](http://onlinehelp.tableau.com/current/pro/desktop/en-us/buildmanual_shelves_pages.html)

**3. Revenue/Budget有0值，如何处理？**

0值在这个变量中代表的是缺失，而不是真的为0，因此在涉及这两个变量的可视化展示时，应当把为0的数据删除。（但如果展示的变量和这两个无关，则不应该删除）

**4.如何在一个工作簿中使用多个数据源？**

点击下图的Data-New Datasource，这样就可以针对不同问题选择不同的数据源。

![](https://i.imgur.com/p6ElUix.png)

**5.使用Revenue还是Revenue_adj？**

推荐使用后缀为adj的变量，因为其考虑了通货膨胀的影响，更为准确。

**6. 如何区分原创电影和改编电影？**

观察“keyword”字段是否含有“based on novel”。


