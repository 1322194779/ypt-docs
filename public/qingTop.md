##### 水环境调度接口地址 
`publicResourceAction!eachJsonQueryTopList.action?newManage.newStatus=1&newManage.newType=6`

###### 请求方式 `get`

##### 数据格式  `json`

```

"result": "success",
"rows": [
  {
    "newStatus": "审批通过",
    "createTime": "2019-06-14 14:40:34 ",
    "publishObject": "公共新闻",
    "institutionId": 15,
    "updateTime": "2019-06-17 11:21:40 ",
    "department": "",
    "newType": "清淤·疏浚",
    "code": "",
    "newManageId": 1250,
    "createTimeNew": 1560494434000,
    "author": "",
    "title": "余杭街道沿山港(小港口-凤新路加油站)清淤疏浚工程施工招标公告",
    "source": "网络转载",
    "times": 2,
    "createTimeDay": "2019-06-14",
    "applicant": "九问采编",
    "imageFile": "",
    "is_recommend": "推荐",
    "appendix": "",
    "approveTime": "",
    "top": "置顶",
    "institution": "萧山区"
  }
]

```    
 

##### 清淤·疏浚详情路由
 ` 
  <router-link tag="div" :to="{'path':'/content',query:{ 'types':'清淤·疏浚', 'id':qingTop.newManageId, 'newType': 8 }}" class="news-list">
    <h1 class="p-title-h1" v-text="qingTop.title"></h1>
    <a v-text="qingTop.introduction"></a>
  </router-link>
 `

##### 清淤·疏浚详情接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=8`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
  {
  "newStatus": "审批通过",
  "createTime": "2019-06-14 14:40:34 ",
  "publishObject": "公共新闻",
  "institutionId": 15,
  "updateTime": "2019-06-17 11:21:40 ",
  "department": "",
  "newType": "清淤·疏浚",
  "code": "",
  "newManageId": 1250,
  "createTimeNew": 1560494434000,
  "author": "",
  "title": "余杭街道沿山港(小港口-凤新路加油站)清淤疏浚工程施工招标公告",
  "source": "网络转载",
  "times": 2,
  "createTimeDay": "2019-06-14",
  "applicant": "九问采编",
  "imageFile": "",
  "is_recommend": "推荐",
  "appendix": "",
  "approveTime": "",
  "top": "置顶",
  "institution": "萧山区"
  }
]
```    
###### 首页->清淤·疏浚更多的列表页路由
```
<router-link class="p-regulate-more" :to="{path:'/list',query:{ 'types':'清淤·疏浚', 'newType': 8 }}">更多</router-link>
```
##### 清淤·疏浚列表接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=8`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
    {
    "newStatus": "审批通过",
    "createTime": "2019-06-14 14:40:34 ",
    "publishObject": "公共新闻",
    "institutionId": 15,
    "updateTime": "2019-06-17 11:21:40 ",
    "department": "",
    "newType": "清淤·疏浚",
    "code": "",
    "newManageId": 1250,
    "createTimeNew": 1560494434000,
    "author": "",
    "title": "余杭街道沿山港(小港口-凤新路加油站)清淤疏浚工程施工招标公告",
    "source": "网络转载",
    "times": 2,
    "createTimeDay": "2019-06-14",
    "applicant": "九问采编",
    "imageFile": "",
    "is_recommend": "推荐",
    "appendix": "",
    "approveTime": "",
    "top": "置顶",
    "institution": "萧山区"
    }
]
```
