##### 接口地址 
`publicResourceAction!commJsonQueryWaterQualityListNew.action?&page=1&rows=10`

###### 请求方式 `get`

##### 数据格式  `json`

```
"result": "success",
"rows": [
{
"createTime": "2019-07-05 23:18:39 ",
"remark": "",
"sectionName": "里周",
"monitorTime": "2019-06-01",
"codMax": "",
"waterQualityMonitorId": 3517,
"transparency": "0.29",
"reach": "唐家溪",
"phValue": 8.59,
"ammoniaNitrogenMax": "",
"grade": 1,
"waterQualityRecordId": 1205760,
"totalNitrogen": "",
"waterQualityInt": 0,
"ammoniaNitrogen": 0.012,
"lat": "29.310059",
"redoxPotential": 164,
"monitorPointCode": "",
"reachId": 2421,
"lon": "119.401119",
"waterQualityMonitor": "HDJD0178",
"moniterLocation": "",
"reachCode": "HDJD0178",
"totalPhosphorus": 0.016,
"sense": "",
"category": "Ⅰ",
"pollutionIndex": "好",
"monitorCompany": "",
"source": "区级抽检",
"cod": 1.8,
"totalNitrogenMax": "",
"monitorType": "",
"waterQualityInstrument": "",
"totalPhosphorusMax": "",
"doValue": 8.3
},]
```    


 
###### 更多的列表页路由
```
<div class="m-title">&nbsp;&nbsp; 河道水质 <router-link tag="div" :to="{path:'WaterQualityList',query:{'nav':'4'}}"   class="t-right f-fr"> <a>更多</a> </router-link></div>
```
##### 列表接口地址  
`publicResourceAction!commJsonQueryWaterQualityListNew.action?&page=1&rows=10`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
{
"createTime": "2019-07-05 23:18:39 ",
"remark": "",
"sectionName": "里周",
"monitorTime": "2019-06-01",
"codMax": "",
"waterQualityMonitorId": 3517,
"transparency": "0.29",
"reach": "唐家溪",
"phValue": 8.59,
"ammoniaNitrogenMax": "",
"grade": 1,
"waterQualityRecordId": 1205760,
"totalNitrogen": "",
"waterQualityInt": 0,
"ammoniaNitrogen": 0.012,
"lat": "29.310059",
"redoxPotential": 164,
"monitorPointCode": "",
"reachId": 2421,
"lon": "119.401119",
"waterQualityMonitor": "HDJD0178",
"moniterLocation": "",
"reachCode": "HDJD0178",
"totalPhosphorus": 0.016,
"sense": "",
"category": "Ⅰ",
"pollutionIndex": "好",
"monitorCompany": "",
"source": "区级抽检",
"cod": 1.8,
"totalNitrogenMax": "",
"monitorType": "",
"waterQualityInstrument": "",
"totalPhosphorusMax": "",
"doValue": 8.3
},]

```

##### 行政区划查询接口

`publicResourceAction!commonJsonQueryInstitution.action?institutionId=3`

###### 请求方式  `get`

##### 数据格式   `json`

```
"result": "success",
"rows": [
{
"employeeId": "3595",
"byCode": "00",
"institutionType": "行政区划",
"groupCode": "",
"checkflag": "通过",
"kind": "县区级机构",
"readIds": "",
"telphone": "15857245623",
"specialMode": "普通台账上传模式",
"authority": "2,7",
"ratioAppendix": "",
"isSuperiorOrganLookOne": "",
"isUpAllowSee": "允许上级查看",
"kindId": 2,
"name": "上城区",
"isSuperiorOrganLook": "",
"institutionParentId": "3",
"isDirectlyAdminLook": "",
"addDate": "2018-04-03",
"isSubordinate": "",
"isDirectlyAdminLookOne": "",
"lat": "",
"lon": "",
"institutionId": 2278,
"masterEmployeeId": "",
"groupPath": "",
"code": "330102",
"address": "",
"special": "普通机构",
"linkman": "上城区",
"countAppendix": ""
},
```
