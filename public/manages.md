##### 接口地址 
`publicResourceAction!eachJsonQueryAllNewManageList.action?newManage.newType=10&newManage.top=1&rows=12`

###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
{
"title": "督查指导制度有哪些具体要求？",
"source": "网络转载",
"createTimeDay": "2019-04-16",
"applicant": "九问采编",
"imageFile": "",
"newType": "治水小常识",
"createTimeNew": 1555384093000,
"newManageId": 1152,
"introduction": "督查指导制度有哪些具体要求？",
"institution": "萧山区"
},]

```    

##### 治水小常识详情路由
  `<ul> <router-link  tag="li" v-for="item in qustionArry2" :key="item.newManageId" :to="{path:'/content',query:{ 'types':'治水小常识', 'id':item.newManageId, 'newType': '10','nav':'4'}}"><a v-html="item.title"></a></router-link> </ul>`
  

##### 详情接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?newManage.newType=10&newManage.top=1&rows=3&page=1`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
{
"title": "督查指导制度有哪些具体要求？",
"source": "网络转载",
"createTimeDay": "2019-04-16",
"applicant": "九问采编",
"imageFile": "",
"newType": "治水小常识",
"createTimeNew": 1555384093000,
"newManageId": 1152,
"introduction": "督查指导制度有哪些具体要求？",
"institution": "萧山区"
},]
```    
###### 水质治理->治水小常识更多的列表页路由
```
<div class="m-title">&nbsp;&nbsp; 治水小常识 <router-link tag="div" :to="{path:'/list',query:{'types':'治水小常识','newType':10,'nav':'4'}}"   class="t-right f-fr">         <a>更多</a> </router-link>
 </div>
```
##### 治水小常识列表接口地址  
`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=10`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
    {
    "title": "督查指导制度有哪些具体要求？",
    "source": "网络转载",
    "createTimeDay": "2019-04-16",
    "applicant": "九问采编",
    "imageFile": "",
    "newType": "治水小常识",
    "createTimeNew": 1555384093000,
    "newManageId": 1152,
    "introduction": "督查指导制度有哪些具体要求？",
    "institution": "萧山区"
    },]
```
##### 治水小常识的图片接口
`publicResourceAction!eachJsonNewManagePictureQueryList.action?newManage.newType=10`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
{
"newStatus": "审批通过",
"createTime": "2018-02-01 10:53:48 ",
"publishObject": "公共新闻",
"institutionId": 287,
"updateTime": "2018-04-11 09:46:05 ",
"department": "",
"newType": "治水小常识",
"code": "萧山网",
"newManageId": 124,
"createTimeNew": 1517453628000,
"author": "",
"title": "治水小常识（三）——经济",
"source": "网络转载",
"times": 12,
"createTimeDay": "2018-02-01",
"applicant": "九问采编",
"imageFile": "newManageImage_124.jpg",
"is_recommend": "不推荐",
"appendix": "",
"approveTime": "",
"top": "置顶",
"institution": "经济开发区"
},
```