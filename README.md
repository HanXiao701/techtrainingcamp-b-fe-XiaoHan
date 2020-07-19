# techtrainingcamp-b-fe-XiaoHan
通过简易版头条搜索API(https://bytedance.feishu.cn/docs/doccnTI8HCO1UDNP0ouZVABI1Ah#AUolGT)完成的搜索页面。
Search.html为搜索主页面，将会调用API的搜索推荐词接口为用户所输入的关键词寻找推荐词并自动显示，在用户点击搜索按钮后将会通过URL传递参数给results.html。
results.html为搜索结果页面，将会接受从自身或者Search.html传来的两个参数，e代表搜索关键词，f代表offset，即搜索页码。
两个页面共同引用style.css作为样式表文件，同时引用assets文件夹中的js及css文件为背景提供动态粒子效果。
--------------------------------------------------------------------------------------------------------------------------------------------A search page completed through the simple headline search API ( https://bytedance.feishu.cn/docs/doccnTI8HCO1UDNP0ouZVABI1Ah#AUolGT ). Search.html is the main search page. The search recommendation interface of the API will be called to find the recommended terms for the keywords entered by the user and automatically displayed. After the user clicks the search button, the parameters will be passed to results.html through the URL.results.html is the search result page, which will accept two parameters from itself or Search.html, e stands for search keywords, f stands for offset, which is the search page number.Both pages refer to style.css as the style sheet file, and refer to the js and css files in the assets folder to provide dynamic particle effects for the background.
