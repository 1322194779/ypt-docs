##### 接口地址 
`publicResourceAction!eachJsonQueryAllNewManageList.action?newManage.newType=3&rows=3&page=1`

###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
    {
    "title": "杭州市治水办卢主任亲自使用云平台app巡河测试",
    "source": "原创",
    "createTimeDay": "2019-06-26",
    "applicant": "九问采编",
    "imageFile": "newManageImage_1290.jpg",
    "newType": "治水动态",
    "createTimeNew": 1561531572000,
    "newManageId": 1290,
    "introduction": "6月26号上午杭州市治水办卢主任亲自下载智慧河道云平台手机app进行现场巡河，并登入管理后台查看系统功能内容，杭州市治水办工作人员以及九问公司技术人员陪同前往。",
    "checker": "杭州市河长办",
    "institution": "萧山区"
    },]

```    

##### 治水动态详情路由
 ` <router-link :to="{path:'/content',query:{ 'types':' 治水动态', 'id':item.newManageId, 'newType': 3,'nav':'1' }}" v-text="'['+item.institution+']'+item.title"></router-link>`
  

##### 详情接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?newManage.newType=3&newManage.top=1&rows=3&page=1`

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
###### 首页->治水动态更多的列表页路由
```
<router-link :to="{path:'/list',query:{ 'types':' 治水动态', 'newType': 3,'nav':'1' }}" class="p-more f-fr">更多</router-link>
```
##### 治水动态列表接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=3`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
    {
   "title": "杭州市治水办陆一奇组长带队到临安督查“污水零直排区”建设工作",
    "source": "网络转载",
    "createTimeDay": "2019-06-20",
    "applicant": "九问采编",
    "imageFile": "newManageImage_1255.png",
    "newType": "治水动态",
    "createTimeNew": 1560994681000,
    "newManageId": 1255,
    "introduction": "6月18日—19日，杭州市治水办陆一奇组长带队到临安督查“污水零直排区”建设工作。 ",
    "checker": "杭州市河长办",
    "institution": "萧山区"
    },]
```
