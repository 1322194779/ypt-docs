##### 小微水体接口地址 
`publicResourceAction!eachJsonQuerySwaterList.action?page=1&rows=6&swater.institution.institutionId=3`

###### 请求方式 `get`

##### 数据格式  `json`

```

"result": "success",
"rows": [
{
"rangeType": "",
"areaNumber": "33010900609",
"dischargePortNum": "",
"sdata": "",
"focusX": "",
"focusY": "",
"location": "横蓬村七组",
"responsibilityUnit": "",
"swaterPollute": "",
"introduce": "",
"type": "池塘",
"gridLat": "",
"rule": "",
"warningWaterLevel": "",
"servicePhone": "",
"waterCode": "CT00010642",
"institution": "南阳街道",
"entryMan": "南阳街道",
"contactPhone": "",
"institutionId": 136,
"standard": "",
"lengthOrArea": "",
"responsibleContact": "",
"image": "",
"problem": "",
"entryDate": "2019-03-18 15:44:55 ",
"gridLon": "",
"waterName": "7组池塘1",
"rectificationDate": "",
"institutionCode": "330109006",
"swaterId": 642,
"normalWaterLevel": "",
"manaUnits": "",
"appendix": ""
},]

```    
 

##### 小微水体信息详情路由
 ```
<router-link class="swater-img"  tag="div" :to="{path:'SwaterInfo',query:{ id:item.swaterId,'nav':'2' }}" v-for="item in waterArry" :key="item.swaterId">
    <div class="swater-img">
    <el-image class="m-banner-img" :src="'common/public/images/'+item.image" width="180px" height="135px">
        <div slot="error" class="image-slot">
        <i class="el-icon-picture-outline"></i>
        </div>
    </el-image>
    </div>
    <span v-html="item.waterName"></span>
    <span class="water-address" v-html="item.location"></span>
</router-link>
```

##### 详情接口地址  
 `publicResourceAction!commJsonQuerySwaterInfo.action?swater.swaterId="+this.$route.query.id`

###### 请求方式  `get`

##### 数据格式   `json`

```
{
"result": "success",
"swater": {
"rangeType": "",
"areaNumber": "",
"dischargePortNum": "",
"sdata": "",
"focusX": "",
"location": "大麦岭—斑竹坞口",
"focusY": "",
"responsibilityUnit": "",
"swaterPollute": "",
"introduce": "",
"type": "",
"gridLat": "",
"rule": "",
"warningWaterLevel": "",
"servicePhone": "",
"waterCode": "STLA000180",
"institution": "临安区",
"entryMan": "杭州市",
"contactPhone": "13868024868",
"institutionId": 2298,
"standard": "",
"lengthOrArea": "2",
"responsibleContact": "毛双喜",
"image": "",
"problem": "防洪能力不足",
"entryDate": "2019-05-30 18:05:37 ",
"gridLon": "",
"waterName": "太源大麦岭小溪",
"rectificationDate": "2016",
"institutionCode": "330185",
"swaterId": 484,
"normalWaterLevel": "",
"manaUnits": "",
"appendix": ""
}
}

```    
###### 水域数据->小微水体更多的列表页路由
```
<router-link tag="div" :to="{path:'ReachList',query:{'nav':'2'}}"   class="t-right f-fr river-more"> <a>更多</a> </router-link>
```
##### 水域数据湖泊/小微水体列表接口地址  
`publicResourceAction!commJsonQuerySwaterInfo.action?swater.swaterId=484`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
{
"rangeType": "",
"areaNumber": "33010900609",
"dischargePortNum": "",
"sdata": "",
"focusX": "",
"focusY": "",
"location": "横蓬村七组",
"responsibilityUnit": "",
"swaterPollute": "",
"introduce": "",
"type": "池塘",
"gridLat": "",
"rule": "",
"warningWaterLevel": "",
"servicePhone": "",
"waterCode": "CT00010642",
"institution": "南阳街道",
"entryMan": "南阳街道",
"contactPhone": "",
"institutionId": 136,
"standard": "",
"lengthOrArea": "",
"responsibleContact": "",
"image": "",
"problem": "",
"entryDate": "2019-03-18 15:44:55 ",
"gridLon": "",
"waterName": "7组池塘1",
"rectificationDate": "",
"institutionCode": "330109006",
"swaterId": 642,
"normalWaterLevel": "",
"manaUnits": "",
"appendix": ""
},]


```
