##### 投诉接口

`taskAction!commonEachJsonSatisfactionPublic.action?page=1&rows=8&o=1`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
{
"total": "1",
"reachId": "1036",
"num": "0.0000",
"reachName": "大东大西横湾",
"unFinish": "0",
"institution": "党湾镇"
},
{
"total": "1",
"reachId": "1988",
"num": "0.0000",
"reachName": "双溪",
"unFinish": "1",
"institution": "大源镇"
}
]
```


##### 更多路由

`<router-link :to="{path:'/rank',query:{ 'types':' 投诉排行榜','nav':5,'active':'2'}}">更多</router-link>`