##### 湖泊/水库信息接口地址 
`publicResourceAction!eachJsonQueryLakeList.action?page=1&rows=5&lake.institution.institutionId=3`

###### 请求方式 `get`

##### 数据格式  `json`

```

"result": "success",
"rows": [
{
"areaNumber": "",
"lakeId": 1536,
"sdata": "",
"imageOld": "1527750164699.jpg",
"contactsOffice": "",
"location": "",
"introduce": "",
"riverInfo": "1532083410482.jpg",
"riverHead": "方从予",
"contacts": "",
"lakeCode": "HPYH00146",
"contactsPhone": "",
"servicePhone": "86269003",
"entryMan": "杭州市河长办",
"institutionId": 33824,
"lakePollute": "",
"image": "1527750164699.jpg",
"code": "",
"entryDate": "2019-04-26 13:48:14 ",
"majorFunction": "灌溉",
"gridLon": "119.7846667",
"riverInfoLocation": "E：119.789538N：30.478707",
"institutionCode": "330110113",
"normalWaterLevel": "",
"rangeType": "",
"scale": "小（二）",
"dischargePortNum": "",
"focusX": "",
"sheriffPhone": "",
"focusY": "",
"responsibilityUnit": "",
"sheriffId": "",
"rainArea": "0.15",
"gridLat": "30.47972222",
"duty": "",
"rule": "",
"grade": "镇级",
"warningWaterLevel": "",
"capacity": "12.04",
"waterQualityInt": 1,
"waterArea": "0.02",
"institution": "黄湖镇",
"office": "党委委员",
"contactPhone": "",
"riverHeadId": 10118,
"lakeName": "狭石弄水库",
"responsibleContact": "",
"isHasSubLake": "",
"sheriffOffice": "",
"lakeOrRovirType": "水库",
"isLand": "",
"rvoirBank": "",
"waterQuality": "Ⅱ",
"telephone": "13758172651",
"RiverInfoOld": "1532083410482.jpg"
},]

```    
 

##### 湖泊/水库信息详情路由
 ```
 <router-link class="fl-lakes" tag="div" :to="{path:'LakeInfo',query:{ id:lakesArry.lakeId,'nav':'2' }}">
    <div class="lake-img">
        <el-image class="m-banner-img" :src="'upload/images/lake/'+lakesArry.image" width="390px" height="408px">
        <div slot="error" class="image-slot">
            <i class="el-icon-picture-outline"></i>
        </div>
        </el-image>
    </div>
    <span class="lakes-txt" v-text="lakesArry.lakeName"></span>
</router-link>
```

##### 详情接口地址  
 `publicResourceAction!commJsonQueryLakeInfo.action?lake.lakeId="+this.$route.query.id;`

###### 请求方式  `get`

##### 数据格式   `json`

```

"rowsLakeHeadArray": [],
"result": "success",
"lake": {
"lakeId": 477,
"areaNumber": "",
"sdata": "",
"location": "",
"introduce": "",
"riverInfo": "1533090630243.jpg",
"riverHead": "",
"lakeCode": "HPXS00007",
"upLakeId": "",
"sheriff": "",
"upLakeName": "",
"servicePhone": "",
"lakeHeadNames": "",
"entryMan": "1212",
"institutionId": 45,
"lakePollute": "",
"image": "1530165070649.jpg",
"code": "",
"entryDate": "2019-06-28 10:24:17 ",
"majorFunction": "防洪/灌溉/",
"riverInfoLocation": "水库西南角",
"gridLon": "120.13",
"institutionCode": "330109101",
"normalWaterLevel": "",
"rangeType": "面",
"scale": "小（二）",
"dischargePortNum": "",
"focusX": "",
"focusY": "",
"responsibilityUnit": "",
"sheriffId": "",
"rainArea": "",
"gridLat": "29.92683333",
"lakeHeadIds": "",
"rule": "",
"warningWaterLevel": "",
"grade": "镇级",
"capacity": "15.68",
"waterQualityInt": 3,
"waterArea": "0.03",
"institution": "河上镇",
"contactPhone": "15025856589",
"riverHeadId": "",
"standard": "",
"lakeName": "里都村大塘坞水库",
"responsibleContact": "",
"lakeShore": "西岸W,南岸S,北岸N,整体A",
"lakeOrRovirType": "水库",
"riverLicy": "",
"isLand": "",
"appendix": "",
"rvoirBank": "",
"waterQuality": "Ⅳ"
},
"rowsLake": [
{
"areaNumber": "",
"lakeId": 1131,
"sdata": "",
"imageOld": "",
"contactsOffice": "",
"location": "",
"introduce": "",
"riverInfo": "",
"riverHead": "",
"contacts": "",
"lakeCode": "HPXS00007&XS&206&2677",
"contactsPhone": "",
"servicePhone": "",
"entryMan": "杭州市",
"institutionId": 15,
"lakePollute": "",
"image": "",
"code": "",
"entryDate": "2019-04-20 16:34:43 ",
"majorFunction": "防洪/灌溉/",
"gridLon": "120.13",
"riverInfoLocation": "",
"institutionCode": "330109",
"normalWaterLevel": "",
"rangeType": "",
"scale": "小（二）",
"dischargePortNum": "",
"focusX": "",
"sheriffPhone": "",
"focusY": "",
"responsibilityUnit": "",
"sheriffId": "",
"rainArea": "",
"gridLat": "29.92683333",
"duty": "",
"rule": "",
"grade": "村级",
"warningWaterLevel": "",
"capacity": "15.68",
"waterQualityInt": "",
"waterArea": "",
"institution": "萧山区",
"office": "",
"contactPhone": "",
"riverHeadId": "",
"lakeName": "里都村大塘坞水库萧山区河上镇里都村段",
"responsibleContact": "",
"isHasSubLake": "",
"sheriffOffice": "",
"lakeOrRovirType": "水库",
"isLand": "",
"rvoirBank": "",
"waterQuality": "",
"telephone": "",
"RiverInfoOld": ""
 }
]


```    
###### 水域数据->湖泊/水库更多的列表页路由
```
   <router-link tag="div" :to="{path:'ReachList',query:{'nav':'2'}}"   class="t-right f-fr river-more"> <a>更多</a> </router-link>
```
##### 水域数据湖泊/水库信息列表接口地址  
`publicResourceAction!commJsonQueryLakeInfo.action?lake.lakeId=477`

###### 请求方式  `get`

##### 数据格式   `json`

```

"rowsLakeHeadArray": [],
"result": "success",
"lake": {
"lakeId": 477,
"areaNumber": "",
"sdata": "",
"location": "",
"introduce": "",
"riverInfo": "1533090630243.jpg",
"riverHead": "",
"lakeCode": "HPXS00007",
"upLakeId": "",
"sheriff": "",
"upLakeName": "",
"servicePhone": "",
"lakeHeadNames": "",
"entryMan": "1212",
"institutionId": 45,
"lakePollute": "",
"image": "1530165070649.jpg",
"code": "",
"entryDate": "2019-06-28 10:24:17 ",
"majorFunction": "防洪/灌溉/",
"riverInfoLocation": "水库西南角",
"gridLon": "120.13",
"institutionCode": "330109101",
"normalWaterLevel": "",
"rangeType": "面",
"scale": "小（二）",
"dischargePortNum": "",
"focusX": "",
"focusY": "",
"responsibilityUnit": "",
"sheriffId": "",
"rainArea": "",
"gridLat": "29.92683333",
"lakeHeadIds": "",
"rule": "",
"warningWaterLevel": "",
"grade": "镇级",
"capacity": "15.68",
"waterQualityInt": 3,
"waterArea": "0.03",
"institution": "河上镇",
"contactPhone": "15025856589",
"riverHeadId": "",
"standard": "",
"lakeName": "里都村大塘坞水库",
"responsibleContact": "",
"lakeShore": "西岸W,南岸S,北岸N,整体A",
"lakeOrRovirType": "水库",
"riverLicy": "",
"isLand": "",
"appendix": "",
"rvoirBank": "",
"waterQuality": "Ⅳ"
},
"rowsLake": [
{
"areaNumber": "",
"lakeId": 1131,
"sdata": "",
"imageOld": "",
"contactsOffice": "",
"location": "",
"introduce": "",
"riverInfo": "",
"riverHead": "",
"contacts": "",
"lakeCode": "HPXS00007&XS&206&2677",
"contactsPhone": "",
"servicePhone": "",
"entryMan": "杭州市",
"institutionId": 15,
"lakePollute": "",
"image": "",
"code": "",
"entryDate": "2019-04-20 16:34:43 ",
"majorFunction": "防洪/灌溉/",
"gridLon": "120.13",
"riverInfoLocation": "",
"institutionCode": "330109",
"normalWaterLevel": "",
"rangeType": "",
"scale": "小（二）",
"dischargePortNum": "",
"focusX": "",
"sheriffPhone": "",
"focusY": "",
"responsibilityUnit": "",
"sheriffId": "",
"rainArea": "",
"gridLat": "29.92683333",
"duty": "",
"rule": "",
"grade": "村级",
"warningWaterLevel": "",
"capacity": "15.68",
"waterQualityInt": "",
"waterArea": "",
"institution": "萧山区",
"office": "",
"contactPhone": "",
"riverHeadId": "",
"lakeName": "里都村大塘坞水库萧山区河上镇里都村段",
"responsibleContact": "",
"isHasSubLake": "",
"sheriffOffice": "",
"lakeOrRovirType": "水库",
"isLand": "",
"rvoirBank": "",
"waterQuality": "",
"telephone": "",
"RiverInfoOld": ""
 }
]

```
