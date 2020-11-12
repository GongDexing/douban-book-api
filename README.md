# 图书API
超级强大的图书数据库，支持图书API调用，通过ISBN查询图书数据，支持10位和13位ISBN，请将 ***{isbn}*** 更换为实际的图书isbn，即可获取图书数据，更多介绍，请搜索“图书数据库”微信小程序，谢谢支持！
```
https://api.ibook.tech/v1/book/isbn?isbn={isbn}&uKey=d2434ac38f394a83aa7c881c7bfb4cb1
```


# 返回数据
json格式，如果 ***errcode*** 为0，表示成功
```json
{
  "errcode": 0,
  "data": {
    "summary": "　　万历十五年，亦即公元1587年，在西欧历史上为西班牙舰队全部出动征英的前一年；而在中国，这平平淡淡的一年中，发生了若干为历史学家所易于忽视的事件。这些事件，表面看来虽似末端小节，但实质上却是以前发生大事的症结，也是将在以后掀起波澜的机缘。在历史学家黄仁宇的眼中，其间的关系因果，恰为历史的重点，而我们的大历史之旅，也自此开始…….本书英文本推出后，被美国多所大学采用为教科书，并两次获得美国书卷奖历史类好书的提名；中文本问世后，获得如潮好评，成为众多作家、学者、企业家、高校师生的案头必备书，并入选《新周刊》和《书城》“改革开放20年来对中国影响最大的20本书”。另有日文、法文、德文等版本。...",
    "author": "(美)黄仁宇著",
    "isbn": "9787101052039",
    "chinaclass": "K248.307",
    "binding": "胶版纸",
    "language": "中文",
    "title": "万历十五年 : 增订纪念本",
    "publisherAddress": "北京",
    "price": "36.00元",
    "publisher": "中华书局",
    "isbn10": "7101052037",
    "page": "264页",
    "category": "历史、地理",
    "pubdate": "2006-08-01"
  },
  "errmsg": "成功"
}
```

# 其他说明
使用过程中有任何问题，可以加微信，请备注“github”，也可以直接搜索“图书数据库”微信小程序，获取更多的图书数据

![微信](https://ibooktech.oss-cn-beijing.aliyuncs.com/project/api/kf.jpg)

