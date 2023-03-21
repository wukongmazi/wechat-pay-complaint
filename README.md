# 微信支付消费者投诉管理系统

https://mp.weixin.qq.com/s/mKa1Gu3LAt01mL31geIQ7g

![Image text](https://picx.zhimg.com/v2-1a15ed334fc40b44e0359853b027f777_1440w.jpg?source=172ae18b)

#### 介绍
当系统在收到用户投诉时会自动回复。如果开启了自动退款，系统收到投诉单后，也会自动退款，然后将投诉单状态改为已处理完成。

![Image text](https://pic2.zhimg.com/80/v2-b2cc69be2ce282fe415abb355a9e159d_720w.webp)

#### 问题背景

玩过微信支付生态的，或许就有这种感受，如果收到投诉单，不会通知到手机端，只会在微信支付商户后台-账户中心-消费者投诉那里显示。那你能一直盯着电脑看吗？可能当你有空打开电脑登录查看的时候，已经积累了好多超时未处理的投诉单。

![Image text](https://pic4.zhimg.com/80/v2-23fa4dbfe5ad52d70d73ff82b92cff2f_720w.webp)

一旦处理不及时，超时什么的，就会受到处罚，比如调整结算周期、关闭自动提现等等。这个时候找不到人工客服，客服电话永远没人接。提交申述，一周就过去了，时间浪费了不说，照样给你维持原判，不带说原因的。欲哭无泪，找谁说理去。

![Image text](https://pic4.zhimg.com/80/v2-0618e479c471b9859cf8f2bf53f2e037_720w.webp)

正好有小伙伴咨询说可以搞个消费者投诉处理系统吗？当然可以。

![Image text](https://pic3.zhimg.com/80/v2-e3392b8a0acc8b9b0bd4bb48adacd49a_720w.webp)

所以还是搞个系统来处理，起码会比较及时的处理投诉单。废话不多说，来看一下这个系统。

#### 商户信息

这里录入的是商户号相关信息，可以新增多个商户号，管理起来也不麻烦，挺方便。

![Image text](https://pic1.zhimg.com/80/v2-adc8280b37ce44b623ac279778e128e0_720w.webp)

要准备商户名称、商户平台apiV3密钥、商户号、商户appid、商户API证书序列号、微信支付平台证书序列号、商户API证书位置路径、微信支付平台证书位置路径，这些参数信息到微信支付商户后台获取。

当系统在收到用户投诉时会自动回复，回复的内容就是获取的【商户回复用户内容】字段的值，所以，这个字段填写的内容要友好、客气、礼貌一点，毕竟，客户可是上帝哦。

![Image text](https://pic1.zhimg.com/80/v2-8b15947a024d0678f4c98f95a124addc_720w.webp)

如果开启了自动退款，系统收到投诉单后，也会自动退款，然后将投诉单状态改为已处理完成。

如果将状态改为禁用，则系统不会收到投诉单通知。

![Image text](https://pic2.zhimg.com/80/v2-451f18b2b333aa99aad6d034105bb6f1_720w.webp)

#### 通知参数

这个配置的是消息通知参数，如果商户号被投诉了，系统收到投诉单时，会通知接收人。有三种通知渠道，邮箱通知、公众号通知、短信通知，任选其一。

![Image text](https://pic1.zhimg.com/80/v2-58de32a7f2c351a9f6825d66b91e7a40_720w.webp)

邮箱通知需要设置发送人邮箱(必须是网易云163邮箱)、发送人邮箱授权码、接收人邮箱。这些需要到网易云163邮箱后台获取。

![Image text](https://pic2.zhimg.com/80/v2-b6ac0037854801391735913936747a61_720w.webp)

公众号通知需要设置公众号appId、公众号secret、公众号模板消息id、接收人公众号openId。这些需要到公众号后台获取。

![Image text](https://pic3.zhimg.com/80/v2-fff12d3f9821554d8051394880058726_720w.webp)

短信通知需要设置腾讯云短信secretId、腾讯云短信secretKey、腾讯云短信模板id、腾讯云短信appId。这些需要到腾讯云后台获取。

![Image text](https://pic4.zhimg.com/80/v2-e91c51b30210f3f72a48933a6816fecb_720w.webp)

公众号后台回复【微信消费者投诉】获取账号密码。

![Image text](https://pic1.zhimg.com/80/v2-fc64ca6384d51bffb28eb6e100c1185c_720w.png)

山水有相逢，来日皆可期，谢谢阅读，我们再会

我手中的金箍棒，上能通天，下能探海
