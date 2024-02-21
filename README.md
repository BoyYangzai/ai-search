# CodeMoss AI搜索引擎

CodeMoss AI搜索引擎（基于ChatGPT和谷歌搜索）

项目初衷：我认为，未来的搜索，不应该在一堆信息里面找答案，应该让AI帮你汇总答案；这个项目就是做这个的，不过目前功能太少，得到的答案不完全对，还需要设计权重算法才行；

<img width='600' src="https://luomacode-1253302184.cos.ap-beijing.myqcloud.com/codemoss-search.png" />

<img width='600' src="https://luomacode-1253302184.cos.ap-beijing.myqcloud.com/codemoss-search2.png" />

## 使用说明

```sh
# 第一步 复制 .env.template 文件，改成 .env

# 第二步：在 .env 文件中配置 OpenAI key 和 Serper KEY

# 第三步：安装依赖
pnpm install

# 第四步：启动
npm run dev

# 第五步：访问下面链接进行使用
http://localhost:3000/
```

## 声明

本项目还未完成，目前还需要解决的问题如下：

- 【功能优化】还不支持流式返回
- 【功能优化】代码写的太烂待优化
- 【功能优化】可配置项太少
- 【功能优化】功能太少

