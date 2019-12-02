# 项目名称：毕业纪念册APP

### BRD：无论是处于什么年龄阶段的用户都有毕业留念的需求，所以此app受众群体大，价值较高。 MRD：基于现今市场上毕业生们对于留念回忆的新技术形式需求，不仅仅像之前的纸质相册那样难以携带，不方便保存，没有记忆点。


### 产品定位
毕业纪念册APP基于所有年龄层的用户都有毕业留念的需求所打造，增加新技术形式，旨在为有需求的用户提供一个回忆、交流、互动的全方位社交平台。

### 价值宣言
毕业纪念册APP用户通过上传自己的毕业相册和允许APP定位自己现居城市，打造社交平台，产品针对性强，比微博微信等社交软件私密性更高。满足用户的联络需求和社交需求。

### 用户痛点
**广泛性**
无论什么年龄层的用户都有毕业留念的需求，毕业纪念册APP受众广泛。

**便携性**
传统的毕业相册厚重，难以保存，不方便携带。毕业纪念册APP安装于手机，便于随时查看翻阅。

**针对性**
针对于相册的储存空间小，用户不记得同学的姓名，不方便用户再联络等痛点。毕业纪念册APP储存空间大，并且具有相应的人脸识别功能，点击即可出现人脸的基本信息。并且可以定位当前用户所在地，绘制班级分布地图，方便用户联络相聚。APP的社区功能也让用户的社交需求得到满足。

### APP功能设计
- app把一个集体的用户现居城市的地图描绘出来，打开app就能看见每个同学的所在地，方便聚会联系。
- 用户上传的每一张照片，应用人脸识别功能，点击每一张人脸，可以出现名字、性别、生日等基本信息。
- 社区功能：注册用户可以发布自己的近照，打造类似朋友圈的社交圈，可以让同学知道自己近况。

### 产品使用场景
毕业纪念册APP相似于微博，微信等社交软件，是用户可以随时打开手机进行浏览的产品。
- 场景一：毕业后同学聚会
利用APP的地图绘制功能，选择所有同学中最适合聚会的地点，对每个同学来说相对路程较短，方便前往。

- 场景二：回忆同学
利用APP的人脸识别功能，用户上传照片后点击人脸，可以出现所识别人脸的名字，性别，年龄，生日，现居地等基本信息。

- 场景三：社交圈
用户闲暇时间翻阅手机打开软件，发布一条动态在社交圈，获得同学的评论和点赞。

### API的使用及其价值主张

1、百度API——人脸识别

价值主张：基于百度深度学习能力的人脸识别技术，提供人脸检测与属性分析、人脸1：1对比、人脸搜索、活体检测等能力。灵活应用于金融、泛安防、零售等行业场景，满足身份核验、人脸考勤、闸机通行等业务需求。

- 接口能力

人脸检测：检测图片中的人脸并标记出位置信息;
人脸关键点：展示人脸的核心关键点信息，及150个关键点信息。
人脸属性值：展示人脸属性信息，如年龄、性别等。
人脸质量信息：返回人脸各部分的遮挡、光照、模糊、完整度、置信度等信息。

- 免费额度


2、高德API——静态地图

价值主张：通过返回一张地图图片响应HTTP请求，使用户能够将高德地图以图片形式嵌入自己的网页中。用户可以指定请求的地图位置、图片大小、以及在地图上添加覆盖物，如标签、标注、折线、多边形。



3、高德API——路径规划

价值主张：路径规划API是一套以HTTP形式提供的步行、公交、驾车查询及行驶距离计算接口，返回JSON 或 XML格式的查询数据，用于实现路径规划功能的开发。 

-适用场景

无需展现地图的场景下，进行线路查询，如以线路结果页形式展现换乘方案；
根据返回线路数据，自行开发线路导航

### API使用错误反馈

- 1、当人脸识别信息错误的时，第一次提示：“啊，用户信息走丢了呢，请再试一次。”第二次提示：“对不起了小主人，我实在无能为力了，要不要问问客服小姐姐呀？”

- 2、当静态地图绘制错误时，提示：“地图绘制错误，已将错误报告反馈给程序员哥哥，请您耐心等待。”之后记录错误信息，及时修改。

- 3、当路径规划路线不正确或者不是最优方案时，提示：“对不起主人，这次考试我又不及格了，已经将错误报告给了程序员哥哥，我会继续努力的。”

### 产品的可行性
1、产品需求明确并且用户市场庞大。
2、产品解决了用户需要毕业留念的用户需求。
3、产品满足了用户同学圈的社交需求。



