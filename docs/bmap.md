### 百度地图

为了使在echarts上更简单的使用百度地图，v-charts封装了一个百度地图的‘壳子’，在settings中添加
关于图表的配置（key,bmap），在组件上直接设置 series, tooltip 等，便可生成以百度地图为坐标系
的 Echarts 图表。

#### 示例

##### 简单地图

<iframe width="100%" height="450" src="//jsfiddle.net/vue_echarts/tvtbz29c/1/embedded/result,html,js/?bodyColor=fff" allowfullscreen="allowfullscreen" frameborder="0"></iframe>

#### 获取地图实例

<iframe width="100%" height="450" src="//jsfiddle.net/vue_echarts/tvtbz29c/2/embedded/result,html,js/?bodyColor=fff" allowfullscreen="allowfullscreen" frameborder="0"></iframe>


#### settings 配置项

| 配置项 | 简介 | 类型 | 备注 |
| --- | --- | --- | --- |
| key | 百度地图 access_key | String | 可[由此](http://lbsyun.baidu.com/apiconsole/key)获取 |
| bmap | 百度地图配置项 | Object | 参考[文档](https://github.com/ecomfe/echarts/tree/master/extension/bmap#使用)配置 |
