##### 接口地址

`publicResourceAction!eachJsonNewManagePictureQueryList.action?newManage.newType=1&newManage.top=1&page=1&rows=1`

```
{
    "total": 1,
    "result": "success",
    "rows": [{
        "newStatus": "审批通过",
        "createTime": "2019-07-10 09:47:07 ",
        "publishObject": "公共新闻",
        "institutionId": 3,
        "updateTime": "",
        "department": "",
        "newType": "新闻动态",
        "code": "",
        "createTimeNew": 1562723227000,
        "newManageId": 9761,
        "checker": "杭州市河长办",
        "author": "",
        "title": "一二三四五六七八九十十一十二十三十四十五十六",
        "source": "原创",
        "times": 16,
        "createTimeDay": "2019-07-10",
        "applicant": "杭州市河长办",
        "imageFile": "newManageImage_9761.jpg",
        "is_recommend": "不推荐",
        "appendix": "",
        "approveTime": "2019-07-10 09:47:16 ",
        "top": "置顶",
        "institution": "杭州市"
    }]
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

`publicResourceAction!eachJsonQueryAllNewManageList.action?newManage.newType=1&rows=2&page=1`

```
{
    "total": 212,
    "result": "success",
    "rows": [{
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
    }, {
        "title": "海宁：大力实施高效节水 促进强农惠农富农",
        "source": "网络转载",
        "createTimeDay": "2018-09-26",
        "applicant": "九问采编",
        "imageFile": "",
        "newType": "新闻动态",
        "createTimeNew": 1537925437000,
        "newManageId": 521,
        "introduction": "“水利是农业生产发展、农村生态宜居、农民生活富裕的基本条件和重要支撑。”近年来，海宁市围绕“乡村振兴”“美丽乡村”“全域旅游”和“大花园”建设，通过推广农业水价综合改革、推进小型农田水利设施提质和开展高效节水灌溉设施等一系列举措，切实改善了农村环境、提高粮食综合生产能力。",
        "institution": "萧山区"
    }]
}
```

###### 热点资讯列表页接口地址

`publicResourceAction!eachJsonQueryAllNewManageList.action?page=1&rows=15&newManage.newType=1`

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