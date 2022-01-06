# FreeDTV

#### 声明

所有资源来自网上, 该软件不参与任何制作, 上传, 储存等内容, 禁止传播违法资源. 该软件仅供学习参考, 请于安装后24小时内删除.

#### 介绍
FreeDTV 免费无广告，也无任何收费会员制倾向，请不要相信任何破解或者收费信息 无内置内容，你可以通过以下接口尝试自己fork接口进行添加修改。


#### 安装教程

下载地址：https://wwi.lanzoui.com/b025mpw7e <br> <br>
项目地址 `https://github.com/FreeDTV/FreeD`<br>

接口地址 `https://cdn.jsdelivr.net/gh/FreeDTV/FreeD/`

 `https://cdn.jsdelivr.net/gh/账号名称/项目名/`
 如果想使用自己fork后的接口名称 将 ``账号名称``替换成自己账号名称，将``项目名``替换成自己的项目名，输入到自建接口内重启应用即可

> 注意:
>
>可能会出现 已经修改或者添加内容但是重启应用后并没有显示 
>这是因为Jsdelivr 缓存如需实时刷新缓存即可如：
> 
>搜索接口：
>https://cdn.jsdelivr.net/gh/FreeDTV/FreeD/searchUrl.json
>
>刷新接口：
>https://purge.jsdelivr.net/gh/FreeDTV/FreeD/searchUrl.json
>
>只需将**cdn** 改为**purge** 强制刷新即可

#### 接口使用说明

##### public.json  公共接口，会有些公共参数配置暂时用不到（通用）
##### searchUrl.json 搜索接口地址 对接苹果CMS10接口（通用）
##### webPlugNavigation.json  云插件接口（通用）<br><br>
##### vipParse.json  VIP解析接口（通用）<br><br>

##### sourceNavigation.json  TV资源专题接口<br><br>

##### category.json     手机版金刚区接口
##### recommend.json     手机版首页推荐接口
##### videoNavigation.json     手机版超级导航接口


#### 如何使用本地接口
保证电视和电脑或者手机在同一WIFI下，启动APP点击开启局域网操作 -> 用手机扫描二维码或者浏览器输入IP地址加端口号
切换到应用设置，自定义接口内输入 **local** 提交即可开启接口本地化
切换到 **网络导入** 输入接口地址点击 **导入** 即可

> 接口地址:
>
>搜索接口：
>https://cdn.jsdelivr.net/gh/FreeDTV/FreeD/searchUrl.json
>
>资源专题接口：
>https://cdn.jsdelivr.net/gh/FreeDTV/FreeD/sourceNavigation.json
>
>云插件接口：
>https://cdn.jsdelivr.net/gh/FreeDTV/FreeD/webPlugNavigation.json
>
>VIP解析接口：
>https://cdn.jsdelivr.net/gh/FreeDTV/FreeD/vipParse.json
>
>
>导入完重启应用，如需简单修改域名切换到相应接口栏修改提交(修改添加必须开启局域网操作)

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request

