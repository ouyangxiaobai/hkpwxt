<h1><span style="font-size: 14pt;"><strong style="color: #ff0000;">项目介绍:</strong></span></h1>
本文介绍了基于协同过滤的航空票务推荐系统的设计与实现，采用了SpringBoot、MySQL、JPA和Freemarker等技术。该系统旨在为用户提供便捷的机票预订服务，并通过协同过滤算法为用户推荐个性化的航班信息。前台用户可以完成注册、登录、浏览首页、预定机票、查看预定详情和订单详情、支付订单、领取优惠券、了解关于我们等功能；而后台用户则具有航空公司管理、飞机管理、机场管理、航班管理、公告管理、客服支持等权限。课题背景源于对航空旅行市场的需求和用户体验的改进。通过实现该系统，可以提高用户对机票预订的满意度和便捷性，同时提供个性化推荐功能，增加用户粘性。未来可以拓展该系统的功能，如增加多种推荐算法、优化用户界面体验、引入航班动态实时更新等，以进一步提升系统的性能和用户体验。

关键词：协同过滤; 机票预订系统; 个性化推荐; 用户体验优化
<h1><span style="color: #ff0000; font-size: 14pt;"><strong>高清视频演示:</strong></span></h1>
<a href="https://www.bilibili.com/video/BV1as421T7cd/">https://www.bilibili.com/video/BV1as421T7cd/</a>
<h1><span style="color: #ff0000; font-size: 14pt;"><strong>系统说明:</strong></span></h1>
<h3><a name="_Toc161847868"></a><a name="_Toc159782347"></a>3.3.1 管理员用例分析</h3>
登录：通过用户名和密码登录系统。

航空公司管理：管理航空公司信息。

飞机管理：管理飞机信息。

飞机舱管理：管理飞机舱位信息。

机场管理：管理机场信息。

航班管理：管理航班信息。

航班动态管理：监督航班的实时状态。

公告管理：发布和管理系统公告。

常见问题：管理常见问题信息。

客服支持：提供客户服务支持。

地域管理：管理地域信息。

优惠券管理：管理优惠券信息。

前台用户列表：查看前台用户信息。

订单列表：查看订单信息。如下图3-1所示：
<img class="alignnone size-full wp-image-61099" src="http://ym.maptoface.com/wp-content/uploads/2024/06/1719846366-c4ca4238a0b9238.png" alt="" width="486" height="298" />

图3-1  管理员用例图
<h3><a name="_Toc161847869"></a><a name="_Toc159782348"></a>3.3.2 用户用例分析</h3>
注册：创建系统账户，提供个人信息。

登录：通过用户名和密码登录系统。

协同过滤推荐：获取个性化的航班推荐。

浏览首页：查看最新的航班信息和活动。

机票预定：选择并预订机票。

预定详情：查看已预订机票的详细信息。

订单详情：查看已支付订单的详细信息。

支付订单：完成机票购买的支付流程。

领取优惠券：获取折扣优惠。

关于我们：了解系统相关信息。

航班动态：查看航班的实时状态。

公告列表：浏览系统发布的公告信息。

客户支持：获取系统使用帮助和客户服务。

个人中心：管理个人信息和订单记录。如下图3-2所示：
<img class="alignnone size-full wp-image-61100" src="http://ym.maptoface.com/wp-content/uploads/2024/06/1719846395-c81e728d9d4c2f6.png" alt="" width="439" height="195" />

图3-2  用户用例图

<img class="alignnone size-full wp-image-61101" src="http://ym.maptoface.com/wp-content/uploads/2024/06/1719846405-eccbc87e4b5ce2f.png" alt="" width="1213" height="699" />
<h1><span style="color: #ff0000; font-size: 14pt;"><strong>适用场景:</strong></span></h1>
<span style="font-size: 18pt;">毕业论文、课程设计、公司项目参考</span>
<h1><span style="color: #ff0000; font-size: 14pt;"><strong>系统截图:</strong></span></h1>
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000001.jpg" alt="图片1" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000003.jpg" alt="图片2" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000004.jpg" alt="图片3" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000005.jpg" alt="图片4" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000006.jpg" alt="图片5" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000007.jpg" alt="图片6" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000008.jpg" alt="图片7" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000009.jpg" alt="图片8" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000010.jpg" alt="图片9" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000011.jpg" alt="图片10" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000012.jpg" alt="图片11" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000013.jpg" alt="图片12" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000014.jpg" alt="图片13" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000015.jpg" alt="图片14" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000016.jpg" alt="图片15" />
<img src="https://99ym.oss-cn-chengdu.aliyuncs.com/1/1/20240313_165444_000017.jpg" alt="图片16" />
