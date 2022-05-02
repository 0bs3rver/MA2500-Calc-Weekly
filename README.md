# MA2500每周推送
本项目可每周计算上证指数MA2500，并通过第三方微信服务号推送。
***项目仅供学习交流之用，请勿用于其它用途。***
项目地址：<https://github.com/KinYuShek/MA2500-Calc-Weekly>
## 特色
- 每周五18点计算上证指数MA2500。
- 支持在 GitHub Actions 或自建服务器上使用
- 支持Server酱消息推送接口

## 使用

### 使用 GitHub Actions 
#### 0. 开始
点击本项目右上角的`Fork`

![](./img/readme-1.png)

#### 1.获取 SendKey
前往<https://sct.ftqq.com/sendkey>
微信扫码关注服务号登录后复制SendKey

![](./img/readme-2.png)

#### 2.添加 SEND Secret
在自己 Fork 后的项目的页面依次点击 `Settings`-`Secrets`-`Actions`-`New repository secret`

![](./img/readme-3.1.png)

![](./img/readme-4.png)

