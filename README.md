# pic-cap

> * picture capture, and upload to store, and get url, for md/html/..., .etc
> * 图片捕获，上传到服务器，获得链接，给 md/html/等其他场景使用

## 截图工具痛点/需求

有需求，欢迎 [crete issue](https://github.com/ReAlign/pic-cap/issues)

* [ ] 标记图形，支持不够丰富【圆形、椭圆等】
* [ ] 透明背景的不规则图形【圆形、菱形等】
* [ ] 不支持 `撤销`/`反撤销` 功能及快捷键【部分工具还是有的】
* [ ] markdown、HTML 使用的全链路支持：
  * [ ] 【用户】
    * [ ] 1.捕获图片
    * [ ] 2.-> 编辑图片
    * [ ] 3.-> 上传图片
    * [ ] 4.-> 生成链接[超链格式/md格式/html格式/...]
    * [ ] 【用户】
  * [ ] 3、4，步骤对用户不可见，直接封装好
* [ ] 精细调节体验太差
  * [ ] 整体：【大小、位置】差 几px，通过拖动很难完全命中
  * [ ] 标记：大小、定位很难让人满意【就算能满意，也要好一通操作】
* [ ] 集成 录屏/gif 功能[issue#1](https://github.com/ReAlign/pic-cap/issues/1)
* [ ] 截屏区域已标记编辑，就不能改变范围了[issue#2](https://github.com/ReAlign/pic-cap/issues/2)
* [ ] ...

## OS[Object Storage] 操作体验

不管是 [NOS](https://www.163yun.com/product/nos) 还是 [OSS](https://oss.console.aliyun.com/overview)（没有接触其他 `OS` 服务），只有生硬的 `API`，个人使用时，完全需要自己搭建可视化环境，很不方便。

* [ ] 官方 `API` 可视化
  * NOS
    * [ ] 增、删、改、查
  * OSS
    * 待完善...

## 版本说明

### 0.0.1-alpha

* 基础截图
  * 详细信息待完善
* nos 可视化
  * 详细信息待完善

下载地址

* [mac-0.0.1-alpha](https://file.realign.pro/pic-cap/0.0.1-alpha/pic-cap-0.0.1-alpha.dmg)
  * [备用地址](http://pkg-realign.test.upcdn.net/pic-cap/0.0.1-alpha/pic-cap-0.0.1-alpha.dmg)
* win-0.0.1-alpha
