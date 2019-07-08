##### 100问接口地址 
`publicResourceAction!eachJsonQueryAllNewManageList.action?newManage.newType=2&page=1&rows=10`

###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
{
"content": "<p class=\"MsoNormal\">\r\n\t<span style=\"font-size:18px;\">“河长制”，即由各级党政主要负责人担任“河长”，负责辖区内河流污染治理。“河长制”是从河流水质改善领导督办制、环保问责制所衍生出来的水污染治理制度。</span>\r\n</p>\r\n<p class=\"MsoNormal\">\r\n\t<span style=\"font-size:18px;\">“河长制”是地方政府对河道水环境治理负责的基本制度，是加强水环境治理的重要抓手。</span>\r\n</p>",
"createTime": "2017-07-18 15:31:53 ",
"title": "什么是“河长制”？",
"applicant": "1212",
"appendix": "",
"newType": "政策制度",
"riverHeadWorkId": 27
},]
```
###### 详情路由

```
<router-link tag="div" :to="{path:'/contents',query:{'id':item.riverHeadWorkId,'nav':'3'}}" class="know-news-list"  v-for="item in questionArry"                   :key="item.riverHeadWorkId">
    <h3 v-html="item.title"></h3>
    <p class="news-text new-text f-fl"  v-html="item.content"></p>
    <span class="f-fr more">详情 <img src="static/images/rivers/more.png" alt=""></span>
        <span class="f-fr news-type" v-html="'栏目'+item.newType"></span>
</router-link>
```
##### 100问识详情接口地址  
`publicResourceAction!commonJsonHundredQuestionContent.action?newManageId=`

###### 请求方式  `get`

##### 数据格式   `json`


```
{
"after": [
{
"title": "“河长制”提出的背景是什么？",
"riverHeadWorkId": 28
}
],
"result": "success",
"front": [],
"rows": {
"content": "<p class=\"MsoNormal\">\r\n\t<span style=\"font-size:18px;\">“河长制”，即由各级党政主要负责人担任“河长”，负责辖区内河流污染治理。“河长制”是从河流水质改善领导督办制、环保问责制所衍生出来的水污染治理制度。</span>\r\n</p>\r\n<p class=\"MsoNormal\">\r\n\t<span style=\"font-size:18px;\">“河长制”是地方政府对河道水环境治理负责的基本制度，是加强水环境治理的重要抓手。</span>\r\n</p>",
"createTime": "2017-07-18 15:31:53 ",
"title": "什么是“河长制”？",
"applicant": "1212",
"appendix": "",
"newType": "政策制度",
"riverHeadWorkId": 27
}
}
```



###### 100问列表页接口地址

`publicResourceAction!eachJsonQueryRiverHeadWorkList.action?page=1&rows=10`

###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
{
"content": "<p class=\"MsoNormal\">\r\n\t<span style=\"font-size:18px;\">“河长制”，即由各级党政主要负责人担任“河长”，负责辖区内河流污染治理。“河长制”是从河流水质改善领导督办制、环保问责制所衍生出来的水污染治理制度。</span>\r\n</p>\r\n<p class=\"MsoNormal\">\r\n\t<span style=\"font-size:18px;\">“河长制”是地方政府对河道水环境治理负责的基本制度，是加强水环境治理的重要抓手。</span>\r\n</p>",
"createTime": "2017-07-18 15:31:53 ",
"title": "什么是“河长制”？",
"applicant": "1212",
"appendix": "",
"newType": "政策制度",
"riverHeadWorkId": 27
},]
```