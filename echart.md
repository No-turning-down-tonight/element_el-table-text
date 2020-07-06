# 使用步骤

1.为echart准备一个大小合适的盒子

		    <div id="main" style="width: 600px;height:400px;"></div>

2.基于准备好的dom,初始化echart实例

​		 `var myChart = echarts.init(document.getElementById('main'))`

3.指定图表的配置项和数据

4. 使用刚指定的配置项和数据显示图表

    `myChart.setOption(option)`

***一般在项目中2和4 步骤都写在mounted生命周期中***

通过 npm 获取 echarts，`npm install echarts --save`

在需要的页面`import echarts from 'echarts'`