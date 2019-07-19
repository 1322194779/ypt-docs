##### 治水成果接口地址 
`publicResourceAction!eachJsonNewManagePictureQueryList.action?newManage.newStatus=1&newManage.newType=4&newManage.top=1&newManage.publishObject=1&rows=2&page=1
`

###### 请求方式 `get`

##### 数据格式  `json`

```

"result": "success",
"rows": [
  {
  "newStatus": "审批通过",
  "createTime": "2019-05-11 13:30:26 ",
  "publishObject": "公共新闻",
  "institutionId": 15,
  "updateTime": "2019-06-17 11:21:57 ",
  "department": "",
  "newType": "治水成果",
  "code": "",
  "newManageId": 1211,
  "createTimeNew": 1557552626000,
  "author": "区五水共治办",
  "title": "点赞！省委书记鼓励肯定了萧山这项工作！",
  "source": "网络转载",
  "times": 35,
  "createTimeDay": "2019-05-11",
  "applicant": "九问采编",
  "imageFile": "newManageImage_1211.jpg",
  "is_recommend": "推荐",
  "appendix": "",
  "approveTime": "",
  "top": "置顶",
  "institution": "萧山区"
  },
]

```    
 

##### 治水成果详情路由
 ` 
 <router-link :to="{'path':'/content',query:{ 'types':' 治水成果', 'id':item.newManageId, 'newType': 4 }}">
    <div class="p-rsimg">
      <el-image :src="'upload/images/newManage/'+item.imageFile">
        <div slot="error"
            class="image-slot">
          <i class="el-icon-picture-outline"></i>
        </div>
      </el-image>
    </div>
    <span v-text="'['+item.institution+']'+item.title"></span>
</router-link>
 `

##### 治水成果详情接口地址  
`publicResourceAction!eachJsonNewManagePictureQueryList.action?newManage.newStatus=1&newManage.newType=4&newManage.top=1&newManage.publishObject=1&rows=2&page=1`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
  {
  "newStatus": "审批通过",
  "createTime": "2019-05-11 13:30:26 ",
  "publishObject": "公共新闻",
  "institutionId": 15,
  "updateTime": "2019-06-17 11:21:57 ",
  "department": "",
  "newType": "治水成果",
  "code": "",
  "newManageId": 1211,
  "createTimeNew": 1557552626000,
  "author": "区五水共治办",
  "title": "点赞！省委书记鼓励肯定了萧山这项工作！",
  "source": "网络转载",
  "times": 35,
  "createTimeDay": "2019-05-11",
  "applicant": "九问采编",
  "imageFile": "newManageImage_1211.jpg",
  "is_recommend": "推荐",
  "appendix": "",
  "approveTime": "",
  "top": "置顶",
  "institution": "萧山区"
  },
]
```    
###### 首页->治水成果更多的列表页路由
```
 <router-link :to="{path:'/list',query:{ 'types':' 治水成果', 'newType': 4 }}" class="p-more f-fr">更多</router-link>
```
##### 治水成果列表接口地址  
`publicResourceAction!eachJsonNewManagePictureQueryList.action?newManage.newStatus=1&newManage.newType=4&newManage.top=1&newManage.publishObject=1&rows=2&page=1`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
  {
  "newStatus": "审批通过",
  "createTime": "2019-05-11 13:30:26 ",
  "publishObject": "公共新闻",
  "institutionId": 15,
  "updateTime": "2019-06-17 11:21:57 ",
  "department": "",
  "newType": "治水成果",
  "code": "",
  "newManageId": 1211,
  "createTimeNew": 1557552626000,
  "author": "区五水共治办",
  "title": "点赞！省委书记鼓励肯定了萧山这项工作！",
  "source": "网络转载",
  "times": 35,
  "createTimeDay": "2019-05-11",
  "applicant": "九问采编",
  "imageFile": "newManageImage_1211.jpg",
  "is_recommend": "推荐",
  "appendix": "",
  "approveTime": "",
  "top": "置顶",
  "institution": "萧山区"
  },
]
```
