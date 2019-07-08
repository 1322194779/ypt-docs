### 前端编码规范

###### HTML规范

1. 区分html和html5 html5的部分标签低版本浏览器不兼容如项目需要兼容低端浏览器则避免使用
2. 使用UTF-8编码```<meta charset="UTF-8">```
3. JS的引入使用应在```head```标签内或者```body```标签底部 特殊情况：模板内的js功能直接放在在html下方
4. 兼容性处理 文档声明告诉浏览器以最高版本来加载页面```<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">```
5. 页面缩放处理```<meta name="viewport" content="width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1,user-scalable=no" />```
6. 避免空标签和无意义标签
7. 其它：小程序使用对方提供的文档标签 一般文档使用 ```div+css``` 布局 钉钉使用```view+acss```

###### CSS规范
> 其它：例如钉钉小程序 使用官方规范布局 ```view+class```


1. 顶级布局:<code>g-</code>
- <code>g-head</code> 代表头部
- <code>g-container</code> 代表内容
- <code>g-center</code> 代表中间
- <code>g-main</code> 代表主体
- <code>g-bottom;g-footer</code> 代表底部
2. 模块布局：<code>m-</code>
- <code>m-video</code> 代表视频模块
- <code>m-image</code> 代表图片模块
- <code>m-left</code> 代表左边
- <code>m-right</code> 代表右边
- <code>m-nav</code> 代表导航
- <code>m-menu</code> 代表菜单
3. 多层次布局：<code>g-head</code>下有<code>m-left;m-left</code>下有左右两个模块可以写成<code>m-l-user;m-r-user</code>
4. 其它布局：使用英文单词缩写前缀或直接使用英文意思 如:<code>content</code>

###### JavaScript规范

1. ID命名方式
    - 驼峰式命名
    - 与所写功能相关 如：视频播放功能 videoPlay
    - 多个相同功能使用英文或数字加以区分 如：videoPlayOne或videoPlay1
2. 变量定义
    - 不可以数字为开头
    - 全局变量声明在最前端
    - 常量使用大写方式 如：USERID、USER_ID
3. 方法定义
    - 与所写功能相关 如：视频播放功能 videoPlay 可以与ID区分加上videoPlayFun
    - 使用驼峰式或者下划线分隔 如：videoPlay video_play
    - 其它：如果使用插件或者npm包则对应使用开发文档的定义
4. 约定写法
    - 在方法内最前位置定义变量和常量
    - ```this```的使用方法 如果没有嵌套作用域直接使用this; 否则使用```var This/that/_this=this;```首选```This```
    - 提高代码可读性 在需要的地方添加注释
4. 应避免的做法
    - 避免使用闭包
    - 避免污染全局作用域
    - 不可使用保留关键字

###### Vue规范

1. 绑定方法使用 ```v-on:click```或者```@click```
2. Vue中ES6代码的兼容方式，引入CDN```<script src="https://cdn.bootcss.com/babel-polyfill/6.23.0/polyfill.min.js"></script>```
3. Vue中的ajax使用框架：```axios```
 
### 其它
weChatPublic
随手拍页面  Task

```<input type="hidden" name="task.issueType" id="task.issueType" value="10" />```

##### 五水共治    TaskXS

```<input type="hidden" name="task.issueType" id="task.issueType" value="11" />```

```
<div class="col-100" style="width: 100%;overflow: hidden;">
								<div class="list-check" style="width: 100%;position: relative;">
									<input style="position: absolute;left: 0;top: 20px;" type="checkbox" id="checkbox15" value="河边不文明行为曝光（向河道乱丢乱扔，洗衣，洗拖把，私自行船，破坏河边绿化，散养家禽）" /> 
									<label for="checkbox15" style="margin-left: 30px;">河边不文明行为曝光（向河道乱丢乱扔，<br />洗衣，洗拖把，私自行船，破坏河边绿化，散养家禽）</label>
								</div>
							</div>
```

##### 热门投诉页面

Hotcomplaints

```<router-link class="new-task" :to="'/Task/'"></router-link>```

HotcomplaintsXS

```<router-link class="new-task" :to="'/TaskXS/'"></router-link>```

部署联通云会出现的问题
图片src问题 /ypt/本地预览 前缀可能要写全

### 其它

兼容IE

- axios传中文需要使用`encodeURI(this.name_search_val)`
- vue中的方法不能简写为 `update_data(){}`需要写成`update_data:function(){}`