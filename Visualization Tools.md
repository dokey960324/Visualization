# Visualization Tools

## Plots on Pandas Dataframes

1. [Seaborn](http://stanford.edu/~mwaskom/software/seaborn/index.html) 基于matplotlib的一个Python可视化图书馆，高度交互性的统计图表

2. [Plotly](https://plot.ly/)
- 非常强大
- 用它设置和创建图形都要花费大量时间
- 安装时要有 API 秘钥，还要注册，不是只用 pip 安装就可以
- Plotly 所绘制的数据和布局对象是独一无二的，但并不直观
- 可以在 Plotly 网站和 Python 环境中编辑图片
- 支持交互式图片和商业报表
- Plotly 与 Mapbox 合作，可以自定义地图
- 很有潜力绘制优秀图形

3. [Plotnine](https://plotnine.readthedocs.io/en/stable/)

4. [日本Bokeh](https://bokeh.pydata.org/en/latest/)
- 一个交互性Python数据可视化插件，在IPython笔记本上直接运行，分享功能很便捷

5. [Pygal](http://pygal.org/en/stable/)
- 由于绘图目标比较简单，因此这是一个相对简单的绘图包
- 用图形框架语法来构建图像
- 实例化图片
- 用图片目标属性格式化
- 用 figure.add() 将数据添加到图片中
- 在文件的创建和渲染部分比较麻烦

6. [Cufflinks](https://github.com/santosjorge/cufflinks)
- 方法统一，参数配置简单
- 可以结合pandas的dataframe随意灵活地画图,可形容为pandas like visualization
- 可生成令人惊叹的3D图表
- [wx上的教程](https://mp.weixin.qq.com/s?__biz=MzA5NDk4NDcwMw==&mid=2651388130&idx=2&sn=5a638e9faff2432e998629c6b24bf7f5&chksm=8bba1872bccd9164c8584fb54716a452a1032ca5d8f3c0d441afd2bbb7b8f3bafaec3c08f8de&mpshare=1&scene=24&srcid=&sharer_sharetime=1565881771989&sharer_shareid=a9f97e3603452f2370ed13a9e54707a6&key=5c697a296e1d5a5c02acb61f10627190f137e4cd1dfc367ead811fbaf2d3a44d1b0f03b501e08af6cded9cd25943bf8c88439b4dd68d9865cd978083baf513e6f5777c8cf770e59132e04e422f39bc55&ascene=14&uin=MTg2MTEyNTMwMA%3D%3D&devicetype=Windows+10&version=62060833&lang=zh_CN&pass_ticket=%2FHDLBDilUmj8WcIiX8l1lDKPk0qC2mKCGvPluaPw352ntaWmj6fc1h7JNoQoAS5Z)
```Python
pip install cufflinks
```
```Python
import cufflinks as cf
```

7. [Folium](https://python-visualization.github.io/folium/)
- 建立在Python生态系统的数据优势和Leaflet.js库的映射优势之上。
- 用于绘制空间数据
- 可生成热图和等值区域图
- 可以为Folium渲染的地图使用不同的地图图层，例如MapBox，OpenStreetMap和其他几个图层
- 可以选择不同的地图投影

8. [pyecharts]


## Drag & Drop to Create Visualizations

1. [Tableau](https://www.tableau.com/zh-cn/products/cloud-bi)

2. [Powei BI](https://powerbi.microsoft.com/zh-cn/landing/signin/?ru=https%3A%2F%2Fapp.powerbi.com%2F%3Froute%3Dgroups%252fme%252fgetdata%252fbigdata%252fsql-server-analysis-services%26noSignUpCheck%3D1)

3. [PixelMap(地图信息化)](https://pixelmap.amcharts.com/#&linkId=173)

## Infographics

