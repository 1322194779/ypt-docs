##### 接口地址

`publicResourceAction!eachJsonNewManagePictureQueryList.action?newManage.newType=1&newManage.top=1&page=1&rows=1`

```
{
    "result": "success",
    "rows": [
        {
            "newStatus": "审批通过",
            "createTime": "2019-07-19 10:56:14 ",
            "author": "",
            "title": "萧禹民间河长护水总队会议顺利召开",
            "source": "原创",
            "createTimeDay": "2019-07-19",
            "applicant": "杭州市河长办",
            "imageFile": "newManageImage_1438.jpg",
            "newType": "新闻动态",
            "createTimeNew": 1563465600000,
            "newManageId": 1438,
            "institution": "杭州市"
        }
    ]
}
```

###### hot_news路由

```
<router-link :to="{path:'/content',query:{ 'types':' 热点资讯', 'id':hot_news.newManageId, 'newType': 1,'nav':'1' }}">
</router-link>
```


###### 首页->更多的列表页路由

```

<router-link :to="{path:'/list',query:{ 'types':' 热点资讯', 'newType': 1 ,'nav':'1'}}" class="p-more f-fr">更多</router-link>
```

###### 首页->热点资讯->2个列表接口地址

`publicResourceAction!eachJsonQueryAllNewManageList.action?newManage.newType=1&rows=2&page=1&newManage.newStatus=1`

```
{
    "total": 366,
    "result": "success",
    "rows": [
        {
            "createTime": "2019-07-22 14:28:31 ",
            "title": "情系企业优服务 环保审批“加速跑”",
            "source": "原创",
            "createTimeDay": "2019-07-22",
            "applicant": "开发区河长办",
            "imageFile": "",
            "newType": "新闻动态",
            "createTimeNew": 1563724800000,
            "newManageId": 1443,
            "introduction": "情系企业优服务 环保审批“加速跑”",
            "institution": "开发区"
        },
        {
            "createTime": "2019-07-22 08:56:04 ",
            "title": "杭州市治水办督查组来萧进行半年度评估检查",
            "source": "网络转载",
            "createTimeDay": "2019-07-22",
            "applicant": "九问采编",
            "imageFile": "",
            "newType": "新闻动态",
            "createTimeNew": 1563724800000,
            "newManageId": 1440,
            "introduction": "7月18日，市治水办考核督查一组周冰副组长一行对萧山区“五水共治”（河长制）工作开展半年度评估检查。区治水办负责人及住建局、农业农村局、城管局、生态环境萧山分局、环境集团等单位相关负责人参加评估座谈。\r\n\r\n",
            "institution": "萧山区"
        }
    ]
}
```

###### 热点资讯列表页接口地址

`publicResourceAction!eachJsonQueryAllNewManageList.action?newManage.newStatus=1&page=1&rows=15&newManage.newType=1`

```
{
    "total": 212,
    "result": "success",
    "rows": [
        {
            "title": "民间护水达人 让萧山河道变得更美",
            "source": "原创",
            "createTimeDay": "2018-09-27",
            "applicant": "九问采编",
            "imageFile": "",
            "newType": "新闻动态",
            "createTimeNew": 1538036892000,
            "newManageId": 537,
            "introduction": "近日，杭州市寻找“民间护水达人”活动正式启动，寻找为“五水共治”工作贡献自身力量的护水人，而这样的民间护水达人，萧山就有不少。",
            "institution": "萧山区"
        }
    ]
}
```