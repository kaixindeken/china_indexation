# 中国经济指数

**注：本仓库为作者自用，无任何参考价值，不构成任何投资建议**

**注：本仓库为作者自用，无任何参考价值，不构成任何投资建议**

**注：本仓库为作者自用，无任何参考价值，不构成任何投资建议**

本项目选取了极少数在香港和美国上市的中国公司，组成自定义指数，尝试判断真实的中国经济市场指标与表现基准，同时给出相应时期的恐慌贪婪指数。其中香港上市公司组合为中国经济基本面指数，是中国经济晴雨表，而美国上市公司组合为中国经济潜力指数，体现中国经济主要增量。具体公司如下：

<table>
<tr>
<td>

* 香港市场

|公司|股票代码|
|:---|:---:|
|工商银行|01398|
|中国银行|03988|
|中芯国际|00981|
|华润置地|01109|
|安踏体育|02020|
|中信银行|00998|
|中国联通|00762|
|联想集团|00992|
|腾讯控股|00700|
|美团-W|03690|
|快手-W|01024|

</td>
<td>

* 美国市场

|公司|股票代码|
|:---|:---:|
|拼多多|PDD|
|阿里巴巴|BABA|
|京东|JD|
|百度|BIDU|
|网易|NTES|
|蔚来|NIO|
|小鹏汽车|XPEV|
|理想汽车|LI|

</td>
</tr>
</table>

本项目使用老虎证券Api，如需使用请将文件 `tiger_openapi_config.properties.example` 更名为 `tiger_openapi_config.properties` ，并参考[这篇文档](https://quant.itigerup.com/openapi/zh/python/overview/openWay.html)进行相关配置。

## Screenshots

![](screenshots/cbfi.png)

![](screenshots/f&g(cbf).png)

![](screenshots/cmii.png)

![](screenshots/f&g(cmi).png)


