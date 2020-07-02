# bokeh-intro
An introduction and some applications in Bokeh. 

`Bokeh-intro`来自于`Python-visualization`库，点击以查看更多的数据可视化介绍：https://github.com/jinlin82/python-visualization

Bokeh Github：https://github.com/bokeh/bokeh

Bokeh 官方教程： https://docs.bokeh.org/en/latest/docs/user_guide.html

### Research Notes

- 2020/05/21  更新了hover，目前需要：(a) 配置hover，能够展示日期，(b) 添加隐藏键，可以选择查看的省份。

- 2020/05/21  更新了hover的感染人数，解决了查看省份选项。目前需要：(a)  统计现有确诊，跟累计确诊放在选择框下。

  (b)  统计全国数据，同时展示累计于新增

  (c)  统计最高10个省份

  (d)  美化目前的图形：坐标轴颜色及其透明度、on_change等。
  
- 2020/07/02  上述内容已经在`analysis.ipynb`文件中更新，`analysis.ipynb`是一个针对新冠疫情数据分析的代码，主要完成了数据可视化等方面的工作。
