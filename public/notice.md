##### 接口地址 
`publicResourceAction!eachJsonQueryAllNewManageList.action?newManage.newType=11&newManage.top=1&rows=3&page=1`

###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
    {
    "title": "水利部办公厅关于征求水利干部职工节约用水行为规范意见的通知",
    "source": "网络转载",
    "createTimeDay": "2019-06-19",
    "applicant": "九问采编",
    "imageFile": "newManageImage_1254.jpg",
    "newType": "通知公告",
    "createTimeNew": 1560908632000,
    "newManageId": 1254,
    "introduction": "为深入贯彻落实“节水优先”方针，弘扬新时代水利精神，《水利干部职工节约用水行为规范详解（征求意见稿）》（见附件2），现征求单位意见。",
    "institution": "萧山区"
    },]

```    
 

##### 通知公告详情路由
 `<router-link :to="{path:'/content',query:{ 'types':' 通知公告', 'id':item.newManageId, 'newType': 11,'nav':'1' }}" v-text="'['+item.institution+']'+item.title"></router-link>`

##### 详情接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?newManage.newType=11&newManage.top=1&rows=3&page=1`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
    {
    "title": "水利部办公厅关于征求水利干部职工节约用水行为规范意见的通知",
    "source": "网络转载",
    "createTimeDay": "2019-06-19",
    "applicant": "九问采编",
    "imageFile": "newManageImage_1254.jpg",
    "newType": "通知公告",
    "createTimeNew": 1560908632000,
    "newManageId": 1254,
    "introduction": "为深入贯彻落实“节水优先”方针，弘扬新时代水利精神，《水利干部职工节约用水行为规范详解（征求意见稿）》（见附件2），现征求单位意见。",
    "institution": "萧山区"
    },]

```    
###### 首页->更多的列表页路由
```
<router-link :to="{path:'/list',query:{ 'types':' 通知公告', 'newType': 11,'nav':'1' }}" class="p-more f-fr">更多</router-link>
```
##### 通知公告列表接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=15`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
    {
    "title": "适宜的农村饮用水消毒方式有哪些？",
    "source": "网络转载",
    "createTimeDay": "2019-01-03",
    "applicant": "萧山区河长办",
    "imageFile": "",
    "newType": "水质小常识",
    "createTimeNew": 1546496666000,
    "newManageId": 838,
    "introduction": "近日，到2020年全省农村饮用水达标人口覆盖率达到95%，基本实现城乡居民同质饮水。",
    "institution": "萧山区"
    },]
```
