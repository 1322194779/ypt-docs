##### 水环境调度接口地址 
`newManageAction!eachJsonQueryTopList.action?newManage.newStatus=1&newManage.newType=7&rows=7&page=1`

###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
    {
        "newStatus": "审批通过",
        "createTime": "2019-06-20 10:09:26 ",
        "publishObject": "公共新闻",
        "institutionId": 15,
        "updateTime": "2019-06-20 10:15:06 ",
        "department": "",
        "newType": "水生态修复",
        "code": "",
        "newManageId": 1256,
        "createTimeNew": 1560996566000,
        "author": "",
        "title": "全国水生态文明城市，浙江又添4个！",
        "source": "网络转载",
        "times": 3,
        "createTimeDay": "2019-06-20",
        "applicant": "九问采编",
        "imageFile": "newManageImage_1256.png",
        "appendix": "",
        "approveTime": "",
        "top": "置顶",
        "institution": "萧山区"
    }
]

```    
 

##### 水生态修复详情路由
 ` 
  <router-link tag="div" :to="{'path':'/content',query:{ 'types':'水生态修复', 'id':repairTop.newManageId, 'newType': 7 }}" class="news-list">
    <h1 class="p-title-h1" v-text="repairTop.title"></h1>
    <a v-text="repairTop.introduction"></a>
  </router-link>

 `

##### 水环境调度详情接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=7`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
    {
    "title": "全国水生态文明城市，浙江又添4个！",
    "source": "网络转载",
    "createTimeDay": "2019-06-20",
    "applicant": "九问采编",
    "imageFile": "newManageImage_1256.png",
    "newType": "水生态修复",
    "createTimeNew": 1560996566000,
    "newManageId": 1256,
    "introduction": "水生态建设是城市建设的重要组成部分，改善水生态环境是增强人民幸福感的重要举措。浙江始终高度重视水生态文明建设，以实现“江河安澜、河湖健康、百业润泽、人水和谐”为主要目标，大力推进水生态文明建设。日前，水利部公布了第二批全国水生态文明城市名单，浙江4地上榜。具体名单:温州市、嘉兴市、衢州市、丽水市。",
    "institution": "萧山区"
    },]
```    
###### 首页->水生态修复更多的列表页路由
```
<router-link class="p-regulate-more" :to="{path:'/list',query:{ 'types':'水生态修复', 'newType': 7 }}">更多</router-link>
```
##### 水生态修复列表接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=7`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
   {
    "title": "全国水生态文明城市，浙江又添4个！",
    "source": "网络转载",
    "createTimeDay": "2019-06-20",
    "applicant": "九问采编",
    "imageFile": "newManageImage_1256.png",
    "newType": "水生态修复",
    "createTimeNew": 1560996566000,
    "newManageId": 1256,
    "introduction": "水生态建设是城市建设的重要组成部分，改善水生态环境是增强人民幸福感的重要举措。浙江始终高度重视水生态文明建设，以实现“江河安澜、河湖健康、百业润泽、人水和谐”为主要目标，大力推进水生态文明建设。日前，水利部公布了第二批全国水生态文明城市名单，浙江4地上榜。具体名单:温州市、嘉兴市、衢州市、丽水市。",
    "institution": "萧山区"
  },
]
```
