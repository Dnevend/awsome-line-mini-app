# awsome-line-mini-app

1、创建 LINE MINI App 应用频道

2、在 Web 应用程序端加载 LIFF SDK

LINE MINI 应用程序作为使用 LIFF（LINE 前端框架）的 LIFF 应用程序运行。因此，首先需要在 Web 应用程序端加载 LIFF SDK。
有两种方法可以加载 LIFF SDK：从 CDN 或使用 npm 包。

```CDN
<script charset="utf-8" src="https://static.line-scdn.net/liff/edge/2/sdk.js"></script>
```

```npm
npm install --save @line/liff
```

3、初始化 LIFF 应用程序

4、实现必要的功能

5、配置 LINE MINI App 频道

6、提交 LINE MINI App 审核

## Reference

- [Medium - 掌握 LINE LIFF：打造便利又互動的應用程式平台](https://medium.com/@jeffchang64/%E6%8E%8C%E6%8F%A1-line-liff-%E6%89%93%E9%80%A0%E4%BE%BF%E5%88%A9%E5%8F%88%E4%BA%92%E5%8B%95%E7%9A%84%E6%87%89%E7%94%A8%E7%A8%8B%E5%BC%8F%E5%B9%B3%E5%8F%B0-86c68dfb673)

- [LINE - 开发者控制台](https://developers.line.biz/)

- [Line Docs - 将网络应用程序作为 LINE MINI 应用程序运行](https://developers.line.biz/en/docs/line-mini-app/develop/web-to-mini-app/)

- [LIFF Playground](https://liff-playground.netlify.app/)
