##### 水环境调度接口地址 
`publicResourceAction!eachJsonQueryTopList.action?newManage.newStatus=1&newManage.newType=6`

###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
    {
    "newStatus": "审批通过",
    "createTime": "2019-06-20 10:38:22 ",
    "publishObject": "公共新闻",
    "institutionId": 15,
    "updateTime": "",
    "department": "",
    "newType": "水环境调度",
    "code": "",
    "createTimeNew": 1560998302000,
    "newManageId": 1257,
    "checker": "杭州市河长办",
    "author": "",
    "title": "美丽江南水乡，还看南湖畔的这座小城！",
    "source": "网络转载",
    "times": 0,
    "createTimeDay": "2019-06-20",
    "applicant": "九问采编",
    "imageFile": "newManageImage_1257.png",
    "is_recommend": "不推荐",
    "appendix": "",
    "approveTime": "2019-06-21 08:34:50 ",
    "top": "置顶",
    "institution": "萧山区"
    }
]

```    
 

##### 水环境调度详情路由
 ` 
 <router-link tag="div" :to="{'path':'/content',query:{ 'types':'水环境调度', 'id':waterTop.newManageId, 'newType': 6,'nav':'1' }}" class="news-list">
    <h1 class="p-title-h1" v-text="waterTop.title"></h1>
    <a v-text="waterTop.introduction"></a>
 </router-link>

 `

##### 水环境调度详情接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=6`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
    {
    "newStatus": "审批通过",
    "createTime": "2019-06-20 10:38:22 ",
    "publishObject": "公共新闻",
    "institutionId": 15,
    "updateTime": "",
    "department": "",
    "newType": "水环境调度",
    "code": "",
    "createTimeNew": 1560998302000,
    "newManageId": 1257,
    "checker": "杭州市河长办",
    "author": "",
    "title": "美丽江南水乡，还看南湖畔的这座小城！",
    "source": "网络转载",
    "times": 0,
    "createTimeDay": "2019-06-20",
    "applicant": "九问采编",
    "imageFile": "newManageImage_1257.png",
    "is_recommend": "不推荐",
    "appendix": "",
    "approveTime": "2019-06-21 08:34:50 ",
    "top": "置顶",
    "institution": "萧山区"
    }
]
```    
###### 首页->水环境调度更多的列表页路由
```
<router-link class="p-regulate-more" :to="{path:'/list',query:{ 'types':'水环境调度', 'newType': 6 }}">更多</router-link>
```
##### 水环境调度列表接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=6`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
    {
    "newStatus": "审批通过",
    "createTime": "2019-06-20 10:38:22 ",
    "publishObject": "公共新闻",
    "institutionId": 15,
    "updateTime": "",
    "department": "",
    "newType": "水环境调度",
    "code": "",
    "createTimeNew": 1560998302000,
    "newManageId": 1257,
    "checker": "杭州市河长办",
    "author": "",
    "title": "美丽江南水乡，还看南湖畔的这座小城！",
    "source": "网络转载",
    "times": 0,
    "createTimeDay": "2019-06-20",
    "applicant": "九问采编",
    "imageFile": "newManageImage_1257.png",
    "is_recommend": "不推荐",
    "appendix": "",
    "approveTime": "2019-06-21 08:34:50 ",
    "top": "置顶",
    "institution": "萧山区"
    }
]
```
