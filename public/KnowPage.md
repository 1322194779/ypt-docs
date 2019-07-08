##### 水质小常识接口地址 
`publicResourceAction!eachJsonQueryAllNewManageList.action?newManage.newType=2&page=1&rows=10`

###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
{
"title": "杭州市治水办在全市河（湖）长制工作培训班上介绍 治水神器—智慧河道云平台",
"source": "原创",
"createTimeDay": "2019-06-13",
"applicant": "九问采编",
"imageFile": "",
"newType": "热点资讯",
"createTimeNew": 1560418981000,
"newManageId": 1246,
"introduction": "6月12日中午，在由杭州市治水办（河长办）联合浙江河（湖）长学院联合举办的“全市河（湖）长制工作培训班”上，杭州市治水办介绍了先进的治水手段。",
"institution": "萧山区"
},]
```
###### 详情路由

```
<router-link :to="{path:'/content',query:{ 'types':' 水质小常识', 'id':hot_news.newManageId, 'newType': 15,'nav':'1' }}"> </router-link>
```
##### 水质小常识详情接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=15`

###### 请求方式  `get`

##### 数据格式   `json`


```
"result": "success",
"rows": [
{
"title": "test",
"source": "网络转载",
"createTimeDay": "2019-04-15",
"applicant": "1212",
"imageFile": "newManageImage_7758.png",
"newType": "水质小常识",
"createTimeNew": 1555323400000,
"newManageId": 7758,
"introduction": "test",
"checker": "1212",
"institution": "萧山区"
},
```


###### 水质治理->水质小常识更多的列表页路由

```
<router-link :to="{path:'/list',query:{ 'types':' 水质小常识', 'newType': 15 ,'nav':'1'}}" class="p-more f-fr">更多</router-link>
```

###### 水质小常识列表页接口地址

`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=15`

###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
{
"title": "test",
"source": "网络转载",
"createTimeDay": "2019-04-15",
"applicant": "1212",
"imageFile": "newManageImage_7758.png",
"newType": "水质小常识",
"createTimeNew": 1555323400000,
"newManageId": 7758,
"introduction": "test",
"checker": "1212",
"institution": "萧山区"
},
```