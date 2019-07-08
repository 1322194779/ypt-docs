##### 排行榜接口

`publicResourceAction!commonJsonQueryRedBlackList.action`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rowsBlack": [
{
"name": "赵伟强",
"reachName": "龙潭里河",
"counts": 4
},
{
"name": "徐国军",
"reachName": "同富门前河",
"counts": 4
},
{
"name": "蒋如祥",
"reachName": "径游小河",
"counts": 4
},
{
"name": "方国华",
"reachName": "后方直河",
"counts": 4
},
{
"name": "328戴村村河长-2",
"reachName": "edqwe",
"counts": 4
},
{
"name": "陈旭东",
"reachName": "西徐盈河",
"counts": 4
},
{
"name": "沈利祥",
"reachName": "老凰桐江",
"counts": 4
},
{
"name": "朱万丰",
"reachName": "曹家弯老河",
"counts": 4
},
{
"name": "徐国军",
"reachName": "同富门前河",
"counts": 4
},
{
"name": "谢哲辉测试6878",
"reachName": "人大河流测试12",
"counts": 4
}
],
"rowsRed": [
{
"name": "下城村级0614勿改",
"reachName": "下城村级0614",
"counts": 8
},
{
"name": "张立康",
"reachName": "南河",
"counts": 6
},
{
"name": "谢哲辉测试6878",
"reachName": "西河",
"counts": 1
},
{
"name": "俞少栋",
"reachName": "下定畈河",
"counts": 0
},
{
"name": "孙渭桥",
"reachName": "塘郎姚河",
"counts": 0
},
{
"name": "项建松",
"reachName": "项家东河",
"counts": 0
},
{
"name": "张婷鸣",
"reachName": "张家河",
"counts": 0
},
{
"name": "蒋如祥",
"reachName": "径游下畈河",
"counts": 0
},
{
"name": "方国华",
"reachName": "张家埭河",
"counts": 0
},
{
"name": "项建松",
"reachName": "草漾河",
"counts": 0
}
]
```


##### 更多路由

`<router-link :to="{path:'/rank',query:{ 'types':' 排行榜','nav':5,'active':'0'}}">更多</router-link>`