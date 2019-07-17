##### 热门投诉接口地址 
`publicResourceAction!commonJsonQueryPublicTaskList.action?page=1&rows=15`

###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
    {
    "taskId": 20361,
    "issueImageTwo": "",
    "issueImageOne": "taskIssueImageOne_20361_0.jpg",
    "taskType": "其他",
    "completeDetail": "",
    "completeTime": "",
    "issueDetail": "瓜沥镇渔庄村瓜渔线于成虎路北五百米池塘填建筑垃圾，以第三次上报了"
    },]

```    
##### 热门投诉详情路由
 ```
   <router-link tag="a" class="e-scale" :to="{path:'/taskcontent',query:{ id:item.taskId,'nav':'1' }}">
        <div class="p-img f-fl">
            <el-image :src="'upload/images/task/'+item.issueImage">
            <div slot="error" class="image-slot">
                <i class="el-icon-picture-outline"></i>
            </div>
            </el-image>
        </div>
        <div class="m-complain-content f-fr">
            <h3 v-text="item.taskType"></h3>
            <p v-text="item.issueDetail"></p>
        </div>
    </router-link>
 ```
  

##### 热门投诉详情接口地址  
`'publicResourceAction!commonJsonTaskContent.action?taskId=' + this.$route.query.id`

###### 请求方式  `get`

##### 数据格式   `json`

```
    {
        "result": "success",
        "task": {
        "dispatchTime": "2019-01-10 17:04:00 ",
        "location": "萧山区",
        "issueType": "随手拍",
        "completeAudio": "",
        "completeDetailTwoFourPlatform": "",
        "dispatcher": "",
        "city": "杭州市",
        "poi": "",
        "approvalTent": "",
        "completeDetailTwo": "",
        "deal": "给四个平台",
        "workTrace": "",
        "completeDetailFourPlatform": "",
        "video": "",
        "sendState": "未发送",
        "approvalTime": "",
        "issueImageOne": "taskIssueImageOne_18667_0.jpg,taskIssueImageOne_18667_1.jpg",
        "polygonCoord": "",
        "completeAudioTwo": "",
        "reexamineDetail": "",
        "issueTime": "2018-12-28 21:31:21 ",
        "isdelete": "未删除",
        "approvalState": "未批示",
        "evaluateTwo": "",
        "issueAddress": "浙江省杭州市萧山区东湖村太来桥西",
        "code": "397620181228093121",
        "issueDetail": "如图所示。",
        "content": "",
        "SiPTSendResult": "无发送结果",
        "geoLatGCJ": "",
        "issueImageTwo": "",
        "evaluate": "满意",
        "geoLonGCJ": "",
        "completePercent": "",
        "taskType": "其他",
        "workPlanDetail": "无",
        "reachName": "无",
        "reachType": "河道",
        "completeCode": "",
        "times": 1,
        "completeVideoTwo": "",
        "completeDetail": "",
        "reachPhoto": "",
        "taskId": 18667,
        "audio": "",
        "outWorker": "匿名",
        "completeImageOne": "",
        "geoLon": 120.434852,
        "superviseStatus": "未督办",
        "completeTimeTwo": "",
        "completeVideo": "",
        "telePhone": "隐藏",
        "outChecker": "",
        "completeImageTwo": "",
        "scoreTwo": "",
        "geoLat": 30.145572,
        "outAccepter": "谢哲辉",
        "reexamineTime": "",
        "taskStatus": "已处理",
        "acceptTime": "2018-12-28 21:31:21 ",
        "assigner": "",
        "SiPTSend": "选择发送",
        "clevel": "",
        "completeTime": ""
        }
    }

```    
###### 首页->热门投诉更多的列表页路由
```
 <router-link tag="div" :to="{path:'tasklist',query:{'nav':'2'}}" class="t-right f-fr more"> <a>更多</a> </router-link>
```
##### 热门投诉列表接口地址  
`publicResourceAction!eachJsonQueryTaskStatusPublicList.action?page="+v+"&rows="+this.page.pageSize+"&task.taskStatus=3&task.issueType=1`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
    {
    "lakeId": "",
    "dispatchTime": "2019-06-26 20:17:01 ",
    "location": "萧山区",
    "issueType": "随手拍",
    "completeAudio": "",
    "completeDetailTwoFourPlatform": "",
    "score": "不满意",
    "dispatcher": "",
    "city": "杭州市",
    "poi": "贡茶(宝龙城市广场店)",
    "completeDetailTwo": "纯纯粹粹",
    "deal": "给河长",
    "happenTime": 1561551420000,
    "completeDetailFourPlatform": "",
    "sendState": "未发送",
    "video": "",
    "approvalTime": "",
    "reachId": 865,
    "issueImageOne": "",
    "completeAudioTwo": "",
    "issueTime": "2019-06-26 20:17:00 ",
    "isdelete": "未删除",
    "image": "",
    "approvalState": "未批示",
    "evaluateTwo": "",
    "issueAddress": "浙江省杭州市萧山区北干街道金鸡路宝龙广场",
    "code": "003520190626081700",
    "portrait": "",
    "issueDetail": "测试\n",
    "content": "",
    "SiPTSendResult": "无发送结果",
    "geoLatGCJ": 30.195987,
    "evaluate": "测试",
    "issueImageTwo": "",
    "supervise": "",
    "geoLonGCJ": 120.254571,
    "completePercent": "",
    "taskType": "水体气味或颜色异常",
    "reachName": "万向河",
    "reachType": "河道",
    "completeCode": "",
    "imageTwo": "",
    "times": 7,
    "completeVideoTwo": "",
    "completeDetail": "猜猜猜",
    "reachPhoto": "wanxiang2.jpg",
    "taskId": 28438,
    "audio": "",
    "outWorker": "匿名",
    "lakeName": "",
    "outWorkerId": 35,
    "completeImageOne": "",
    "geoLon": 120.250104,
    "superviseStatus": "未督办",
    "completeTimeTwo": "2019-06-26 20:19:39 ",
    "completeVideo": "",
    "scoreTwo": "",
    "telePhone": "***********",
    "outChecker": "",
    "completeImageTwo": "",
    "geoLat": 30.198445,
    "outAccepter": "屠锦铭",
    "reexamineTime": "",
    "taskStatus": "已处理",
    "acceptTime": "2019-06-26 20:17:00 ",
    "assigner": "",
    "SiPTSend": "选择发送",
    "clevel": "",
    "completeTime": "2019-06-26 20:17:21 "
    } ]
```
