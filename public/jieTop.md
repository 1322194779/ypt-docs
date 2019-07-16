##### 截污纳管接口地址 
`publicResourceAction!eachJsonQueryTopList.action?newManage.newStatus=1&newManage.newType=5`
###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
    {
    "newStatus": "审批通过",
    "createTime": "2019-06-14 13:59:10 ",
    "publishObject": "公共新闻",
    "institutionId": 15,
    "updateTime": "2019-06-17 11:21:50 ",
    "department": "",
    "newType": "截污纳管",
    "code": "",
    "newManageId": 1247,
    "createTimeNew": 1560491950000,
    "author": "",
    "title": "美丽杭州环保先行：上城区截污纳管有“法宝”",
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
 

##### 截污纳管详情路由
 `
 <router-link tag="div" :to="{'path':'/content',query:{ 'types':'截污纳管', 'id':jieTop.newManageId, 'newType': 5 ,'nav':'1'}}" class="news-list">
    <h1 class="p-title-h1" v-text="jieTop.title"></h1>
    <a v-text="jieTop.introduction"></a>
 </router-link>
    `
 

##### 截污纳管详情接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=5`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
{
"title": "美丽杭州环保先行：上城区截污纳管有“法宝”",
"source": "网络转载",
"createTimeDay": "2019-06-14",
"applicant": "九问采编",
"imageFile": "",
"newType": "截污纳管",
"createTimeNew": 1560491950000,
"newManageId": 1247,
"introduction": "杭州有个好法宝，一种智能治水的新武器：气流井。与过去的截流井相比，气流井对雨量的测定更加精准，可以通过自动或者人工的方式控制闸门。雨天再也不用担心雨污分流了。",
"institution": "萧山区"
},]

```    
###### 首页->截污纳管更多的列表页路由
```
<router-link class="p-regulate-more" :to="{path:'/list',query:{ 'types':'截污纳管', 'newType':5,'nav':'1' }}">更多</router-link>
```
##### 截污纳管列表接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=5`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
    {
    "title": "美丽杭州环保先行：上城区截污纳管有“法宝”",
    "source": "网络转载",
    "createTimeDay": "2019-06-14",
    "applicant": "九问采编",
    "imageFile": "",
    "newType": "截污纳管",
    "createTimeNew": 1560491950000,
    "newManageId": 1247,
    "introduction": "杭州有个好法宝，一种智能治水的新武器：气流井。与过去的截流井相比，气流井对雨量的测定更加精准，可以通过自动或者人工的方式控制闸门。雨天再也不用担心雨污分流了。",
    "institution": "萧山区"
    },]
```
