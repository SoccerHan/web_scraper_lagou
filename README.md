# 使用chrome插件web_scraper抓取拉勾上的岗位数据教程
>step1 打开拉勾首页
>![拉勾首页](https://github.com/SoccerHan/web_scraper_lagou/blob/master/拉勾首页.jpg)

>step2 输入岗位，如：新媒体
>![输入岗位后检索](https://github.com/SoccerHan/web_scraper_lagou/blob/master/拉勾-输入职位.jpg)

>step3 鼠标右击，检查该页面
>![检查页面](https://github.com/SoccerHan/web_scraper_lagou/blob/master/右键检查.jpg)

>step4 切换到web_scraper面板
>![切换面板](https://github.com/SoccerHan/web_scraper_lagou/blob/master/切换到web_scraper.jpg)

>step5 创建sitemaps，复制该页面的地址，粘贴到URL中
>![复制链接](https://github.com/SoccerHan/web_scraper_lagou/blob/master/复制链接.jpg)
>![创建新的sitemaps](https://github.com/SoccerHan/web_scraper_lagou/blob/master/创建demo.jpg)

>step6 创建完成后，在路径root下，创建点击：*add new selector*
>![在_root路径下新增selector](https://github.com/SoccerHan/web_scraper_lagou/blob/master/_root路径下.jpg)

>step7 选择element
>鼠标悬停的状态，为绿色的，表示为可选择
>![选择element状态](https://github.com/SoccerHan/web_scraper_lagou/blob/master/element鼠标悬停状态.jpg)
>红色，表示已经点击选择了
>![单选状态](https://github.com/SoccerHan/web_scraper_lagou/blob/master/element单选.jpg)
>再次点击，会选择该页面的所有相同元素
>![多选状态](https://github.com/SoccerHan/web_scraper_lagou/blob/master/element多选.jpg)

>step8 选择element click,拖动页面到最下面，有页码切换栏，选中：*下一页*
>![element_click元素选择](https://github.com/SoccerHan/web_scraper_lagou/blob/master/element_click选择.jpg)
>![分页元素选择](https://github.com/SoccerHan/web_scraper_lagou/blob/master/element_click选择.jpg)

>step9 如图完成配置
>![配置](https://github.com/SoccerHan/web_scraper_lagou/blob/master/如图配置好内容，保存.jpg)

>step10 点击*item*栏，进入下一级路径 **_root/item**
>![下一级路径](https://github.com/SoccerHan/web_scraper_lagou/blob/master/进入下一级目录.jpg)

>step11 在路径 **_root/item** 单击 *add new selector*，类型为*click*，如图选择红色框。完成创建后，点击红色框，页面跳转到下一级，如下图所示
>![类型link的选择器](https://github.com/SoccerHan/web_scraper_lagou/blob/master/link选择.jpg)

>step12 同理，*add new selector*，类型：*text*,选择岗位，完成
>![选择要抓取的字段：岗位，类型为：text](https://github.com/SoccerHan/web_scraper_lagou/blob/master/选择岗位名称.jpg)

>step13 同上，对该页面要抓取的文本进行选择，并最终可发现sitemaps的结构为这样。点击：sitemaps name → selector graph，可见
>![sitemaps完整结构图](https://github.com/SoccerHan/web_scraper_lagou/blob/master/sitemaps树状图.jpg)

>step14 点击：sitemaps name，本次演示为：sitemaps new_media_demo，会下拉展开菜单，点击：*scraper*
>![点击开始抓取](https://github.com/SoccerHan/web_scraper_lagou/blob/master/点击scraper.jpg)

>step15 静静等待，chrome会发生响应，然后进行网页抓取，此时不要关闭浏览器。待浏览器提醒完成后，点击：*export data as CSV*
>![导出CSV](https://github.com/SoccerHan/web_scraper_lagou/blob/master/导出CSV.jpg)

>step16 done，恭喜你，可以进行岗位能力的萃取了。如有疑问，请微信：SoccerHan















